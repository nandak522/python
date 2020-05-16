# python
Base Image for all python (v3) apps

---
## Build Docker Images
> `<version>` mentioned below is defined in `VERSION.txt` file.
```sh
# base image for nanda/hello-universe
docker build -t nanda/python:<version> .
```

---
## Run Docker Container
> `<version>` mentioned below is defined in `VERSION.txt` file.
```sh
# run base image's container
docker run -it nanda/python:<version>
```
