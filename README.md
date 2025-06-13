## 1. Build Docker image 
```commandline
docker build -t python-rest-api .
```

## 2. Run Docker image
```commandline
docker run -p 9001:9001 python-rest-api
```


## 3. push the image to Docker hub

```commandline
docker tag python-project  python-project:python

```
