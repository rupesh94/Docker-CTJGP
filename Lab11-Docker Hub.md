## Common Docker Hub Commands

Search for Images
```
docker search <keyword>
```

Pull an Image from Docker Hub
```
docker pull <image-name>:<tag>
```

List Local Images
```
docker images
```

Create an Image (Using docker build or coomit)
```
docker build -t my-app:1.0 .
```
Tag the Image:
```
docker tag my-app:1.0 myusername/my-app:1.0
```

Login to Docker Hub
Before pushing or pulling images to/from Docker Hub, you need to log in:
```
docker login
```
You will be prompted for your Docker Hub username and password.
Push the Image:
```
docker push myusername/my-app:1.0
```

