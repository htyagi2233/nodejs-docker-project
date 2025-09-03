# 🧪 Project-1: Node.js Web Application Deployment on Docker with Jenkins
Node.js Web Application Deployment on Docker with Jenkins का project structure दिया है, मैं आपको same-to-same lab setup बनाकर दूँगा step-by-step, ताकि आप सीधे अपने test server पर try कर सको।
ये project 3 parts में होगा:
- 1. Node.js App Setup on Server
- 2. Dockerize the Node.js App
-	3. Jenkins Pipeline for CI/CD

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
    └── package-lock.json<img width="1148" height="602" alt="image" src="https://github.com/user-attachments/assets/d14d499e-e611-4b52-b697-9b969234f789" />
```

Go to NodeJs Officially Site ->  <https://nodejs.org/en/download>
And install Node.js on test Server
<img width="696" height="40" alt="image" src="https://github.com/user-attachments/assets/cee10ee3-cf84-4012-958b-5fef84f32293" />

	# Download and install nvm on our a Server:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```



