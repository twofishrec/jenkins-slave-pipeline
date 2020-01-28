## Jenkins Container

This project contains a Dockerfile to build a Jenkins container image that can be used to run jenkins jobs and build container images within the pipeline jobs.

This project can be build using:

 ```$ docker build -t myproject\jenkins .```

This will build the image that can then be started using the docker compose file:

 ```$ docker-compose -f docker-compose-withdocker.yml up ```


To Do
Add Configuration to automatically install the Docker plugin to faciltate using slave images for builds.

This plugin gets configured in the Cloud configuration tab. 
![Image description](https://github.com/twofishrec/jenkins-slave-pipeline/blob/sanitized/images/configuringClouds.png)

