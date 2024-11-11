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
docker tag my-app:1.0 meharcloudthat/my-app:1.0
```

Log in to Docker Hub before pushing images to Docker Hub. You will be prompted for your Docker Hub username and password
```
docker login
```


Push the Image:
```
docker push meharcloudthat/my-app:1.0
```

