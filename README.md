My Node.js CI/CD Project
This project demonstrates a complete CI/CD pipeline using GitHub Actions to automatically test, build, and push a Node.js application as a Docker image to Docker Hub.

Task Submission Information
To evaluate this task, please use the following information:

GitHub Repository: https://github.com/Arman-Bisht/my-node-app

Docker Hub ID: arman377

Docker Image Repository: https://hub.docker.com/r/arman377/my-node-app/tags

How the Pipeline Works
The CI/CD workflow is defined in the .github/workflows/ci-cd.yml file and is triggered on every push to the main branch.

The pipeline performs the following steps:

Checks out the source code.

Sets up a Node.js environment.

Installs project dependencies using npm install.

Runs tests (currently a placeholder script).

Logs into Docker Hub using secrets for both the username and password.

Builds a Docker image of the application.

Pushes the image to Docker Hub with two tags: latest and the commit SHA.