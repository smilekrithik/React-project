Steps to Automate Deployment
Push to GitHub:

Commit your changes and push the React code to your GitHub repository.
Jenkins CI/CD Pipeline:

Jenkins will automatically pull the latest code from GitHub when changes are pushed to the main branch.
The pipeline will build the Docker image, run tests, push the image to Docker Hub, and deploy the application to Kubernetes.
Docker Hub:

Docker Hub stores the Docker image that can be used to deploy the application anywhere.
Kubernetes:

Kubernetes will use the latest Docker image from Docker Hub and manage the deployment of your application.
