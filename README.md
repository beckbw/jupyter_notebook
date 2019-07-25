# Science in the Cloud 2019

## Docker image containing Jupyter notebook

* To build

```$ docker build -t <dockerhub username>/jupyter_notebook:<version> .```

* To run

```$ docker run -p 80:8888  <dockerhub username>/jupyter_notebook:<version>```

* To run (with mount)

```$ docker run -p 80:8888  -v $PWD/data:/home/jupyter/work <dockerhub username>/jupyter_notebook:<version>```
