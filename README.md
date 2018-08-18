# Build Django Docker Image With Alpine

This is intent to use as reference when trying to build Django image with Alpine. Unlike Ubuntu based image, Alpine doesn't have most of the build in packages that are required for everyday usage Django. Hopefully it cover all the packages.

If you have other packages that required by Django and was not include in the `alpine_dockerfile` you can help other by making pull request.

## Running This Project
```bash
$ docker-compose up --build
```
