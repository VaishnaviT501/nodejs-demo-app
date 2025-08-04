Tools Used:
  - GitHub
  - GitHub Actions
  - Docker & DockerHub
  - Node.js

Created a sample Node.js app. 
Added a Dockerfile to containerize the app. 
Built and tested the Docker image locally using Docker Desktop.
Pushed the image to DockerHub. Created a main.yml file that:
   - Runs on every push to 'main'
   - Builds the Docker image
   - Pushes it to DockerHub automatically
Added DockerHub Credentials using GitHub secrets.
