This is a CICD Project implemented with Jenkins.

Technologies Used in this project: 
1️⃣ Continuous Integration with Jenkins:
Whenever changes are pushed to GitHub, Jenkins triggers the pipeline to fetch the latest code. It conducts unit tests to validate functionality and checkstyle tests to maintain code quality.

2️⃣ Code Analysis with SonarQube:
The project undergoes comprehensive code analysis on SonarQube, hosted on an AWS EC2 instance. SonarQube identifies bugs, vulnerabilities, and assesses code quality, presenting detailed reports on its intuitive web interface.

3️⃣ Containerization with Docker and AWS ECR:
After successful testing and analysis, the artifact is securely stored in Amazon ECR (Elastic Container Registry) as a Docker image. This ensures consistency across environments and facilitates easy deployment.

4️⃣ Deployment on Amazon ECS:
Amazon ECS (Elastic Container Service) retrieves the Docker image from ECR and orchestrates its deployment as containerized applications. This scalable and reliable approach optimizes resource management and enhances application availability.
