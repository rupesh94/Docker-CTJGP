## Common Docker Hub Commands

Search for Images
```
docker search ubuntu
```

Pull an Image from Docker Hub
```
docker pull ubuntu
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
You need to log in before pushing or pulling images to/from Docker Hub.You will be prompted for your Docker Hub username and password
```
docker login
```


Push the Image:
```
docker push myusername/my-app:1.0
```

