build command: 
```
docker build -t w1_lab .
```
to run the container:
```
docker run -d --name w1_lab -p 80:80 w1_lab
```
see running containers:
```
docker ps
```

dockerfile reference: https://docs.docker.com/reference/dockerfile/