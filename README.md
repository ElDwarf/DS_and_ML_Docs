#Tensorflow Course

## Build docker

```
$ docker build -t tensorflow-p3-opencv:lates .
```

## Run docker

```
$ docker run -it --rm -v $(pwd)/notebooks:/tf/notebooks -v $(pwd)/dataset:/tf/dataset -p 8888:8888 tensorflow-p3-opencv:lates
```
