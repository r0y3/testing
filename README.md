Testing Inside Docker
=====================

Sample project to showcase doing unit testing inside docker container.

**NOTE:** I made changes to some maintainer information in the Dockerfile but credits should be given to the original author.

Building Docker Image
---------------------

```bash
docker build -t py_unittest .
```

Running the Test
----------------

```bash
docker run --rm -it py_unittest .
```
