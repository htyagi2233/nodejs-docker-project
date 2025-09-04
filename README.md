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
### ................................................... Installaion process on test server ................................................................................................................

- Go to NodeJs Officially Site ->  <https://nodejs.org/en/download>-
- And install Node.js on test Server
	
### Copy first command and run on test Server-
```
	curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```
	
