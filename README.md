# jenkins-no-wizard
This docker image extends the official Jenkins image. The wizard and user authentication are disabled.

The aim is to provide a quick way to run a Jenkins server used for testing: no wizard to run, no authentication to configure.


* Build and run locally:
```
docker build -t jenkins-no-wizard .
docker run -p 8080:8080 jenkins-no-wizard
```

* Run using the docker hub image:
```
docker run -p 8080:8080 remydewolf/jenkins-no-wizard
```
