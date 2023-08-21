#Build docker image
```
docker build -t <image name> .
```

#find docker images
```
docker images
```

#To run docker
```
docker run -p 5000:5000 <image name>
```

#to find running containers
```
docker ps
```

#to stop running docker image
```
docker stop <image id>
```

#delete the image
```
docker image rm -f <image name>
```

#push docker image into docker hub
```
docker push maharengarajan/welcome-app:latest
```

#to pull docker image
```
docker pull maharengarajan/welcome-app:latest
```