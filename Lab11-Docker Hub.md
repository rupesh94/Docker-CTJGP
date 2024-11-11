Common Docker Hub Commands:
1. Login to Docker Hub
Before pushing or pulling images to/from Docker Hub, you need to log in:

bash
Copy code
docker login
You will be prompted for your Docker Hub username and password.
2. Pull an Image from Docker Hub
Download an image from Docker Hub:

bash
Copy code
docker pull <image-name>:<tag>
Example: docker pull nginx:latest pulls the latest version of the official nginx image.
3. Push an Image to Docker Hub
Upload an image to Docker Hub:

bash
Copy code
docker tag <local-image> <dockerhub-username>/<repository>:<tag>
docker push <dockerhub-username>/<repository>:<tag>
Example:
bash
Copy code
docker tag my-app:1.0 myusername/my-app:1.0
docker push myusername/my-app:1.0
4. Search for Images
Search for images directly from the command line:

bash
Copy code
docker search <keyword>
Example: docker search ubuntu lists all publicly available images related to Ubuntu.
5. List Local Images
Show images stored locally on your machine:

bash
Copy code
docker images
Steps to Upload an Image to Docker Hub:
Create an Image (e.g., using docker build):
bash
Copy code
docker build -t my-app:1.0 .
Tag the Image:
bash
Copy code
docker tag my-app:1.0 myusername/my-app:1.0
Push the Image:
bash
Copy code
docker push myusername/my-app:1.0
