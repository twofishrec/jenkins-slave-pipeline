## Jenkins Container

This project contains a Dockerfile to build a Jenkins container image that can be used to run jenkins jobs and build container images within the pipeline jobs.

This project can be build using:

 ```$ docker build -t dso\jenkins .```

This will build the image that can then be started using the docker compose file:

 ```$ docker-compose -f docker-compose-withdocker.yml up ```
