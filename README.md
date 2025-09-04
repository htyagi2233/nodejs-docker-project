# ('' 🧪 Project-1: Node.js Web Application Deployment on Docker with Jenkins '')
- Node.js Web Application Deployment on Docker with Jenkins का project -structure दिया है, मैं आपको same-to-same lab setup बनाकर दूँगा step-by-step, ताकि आप सीधे अपने test server पर try कर सको।
- ये project 3 parts में होगा:
	- Node.js App Setup on Server
	- Dockerize the Node.js App
	- Jenkins Pipeline for CI/CD

## 1️⃣ Project Directory Structure
<https://github.com/htyagi2233/nodejs-docker-project.git>

```
nodejs-docker-project
├── package.json
├── package-lock.json
├── public
│   ├── images
│   │   └── nodejs-logo.png
│   ├── index.html
│   └── styles.css
├── README.md
├── src
│   ├── app.js
│   └── imageDisplay.js
└── tests
    ├── imageDisplay.test.js
    ├── package.json
    └── package-lock.json

```
### ................................................... Installaion process on test server ........................................................................................

- Go to NodeJs Officially Site ->  <https://nodejs.org/en/download>-
- And install Node.js on test Server
	
### Copy first command and run on test Server-
```
	curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```
	
### Command install होने के बार output में हमें 3 command मिलेंगी अब हमें इस 3 command को run करना है test server पर 

```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion



# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 22

# Verify the Node.js version:
node -v # Should print "v22.19.0".
nvm current # Should print "v22.19.0".

# Verify npm version:
npm -v # Should print "10.9.3".

```


###  This file is available in GitHub Repository 
< https://github.com/htyagi2233/nodejs-docker-project.git >

```
# cat package.json

{
  "name": "my-nodejs-spa",
  "version": "1.0.0",
  "description": "A Node.js SPA project with Jest tests",
  "main": "src/app.js",
  "scripts": {
    "start": "node src/app.js",
    "test": "jest"
  },
  "dependencies": {
    "express": "^4.19.2"
  },
  "devDependencies": {
    "jest": "^27.5.1"
  },
  "directories": {
    "test": "tests"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}

```


### So based on this file we will installed dependency 
```
# npm install express
# npm install --save-dev jest
# npm start
```

### Copy the Jenkins Server ip and browse with 3000 port 
- Server is running on http://0.0.0.0:3000

<img width="1202" height="1232" alt="image" src="https://github.com/user-attachments/assets/ecb2827e-baf3-4c55-bcd2-a726b4118b0d" />
