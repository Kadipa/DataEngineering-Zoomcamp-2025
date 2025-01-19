#Module-1 (Notes)

1. What is Docker?
Docker is an open-source platform designed to automate the deployment, scaling, and management of applications using containerization. Containers encapsulate an application and its dependencies, ensuring consistent behavior across various environments.

2. Pipeline Overview The video outlines a typical CI/CD pipeline incorporating Docker:
Development: Developers write code and define application environments using Dockerfiles.
Build: Docker images are built from Dockerfiles, containing the application and its dependencies.
Testing: Containers instantiated from these images are used to run automated tests, ensuring reliability.
Deployment: Tested images are deployed to production environments, facilitating seamless updates and rollbacks.

3. Why Docker Containers? The video highlights several advantages of using Docker containers:
Consistency: Containers ensure applications run the same, regardless of the underlying infrastructure.
Isolation: Each container operates independently, preventing conflicts between applications.
Scalability: Containers can be easily scaled horizontally to handle increased load.
Efficiency: Containers are lightweight, allowing for high-density deployment on hosts.

4. Running Docker The video demonstrates basic Docker commands:
docker run: Creates and starts a new container from a specified image.
docker build: Builds a Docker image from a Dockerfile.
docker pull: Downloads an image from a Docker registry.
docker push: Uploads an image to a Docker registry.