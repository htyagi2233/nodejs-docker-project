# 🧪 Project-1: Node.js Web Application Deployment on Docker with Jenkins
Node.js Web Application Deployment on Docker with Jenkins का project structure दिया है, मैं आपको same-to-same lab setup बनाकर दूँगा step-by-step, ताकि आप सीधे अपने test server पर try कर सको।
ये project 3 parts में होगा:
- 1. Node.js App Setup on Server
- 2. Dockerize the Node.js App
-	3. Jenkins Pipeline for CI/CD

### 1️⃣ Project Directory Structure
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
<img width="914" height="708" alt="image" src="https://github.com/user-attachments/assets/4fc38fd1-ebcf-4e53-b349-55593a830fdc" />


	# Download and install nvm on our a Server:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash<img width="822" height="20" alt="image" src="https://github.com/user-attachments/assets/ab6aebb2-2801-4f7f-b9b8-3981738da217" />

```



