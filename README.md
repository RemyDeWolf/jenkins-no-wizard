# jenkins-no-wizard
Extend the official Jenkins image, but turns off the wizard, disable authentication.

To be used for testing, provide quick Jenkins server up and running.


* Build and run locally:
```
docker build -t jenkins-no-wizard .
docker run -p 8080:8080 jenkins-no-wizard
```

* Run using the docker hub image:
```
docker run -p 8080:8080 remydewolf/jenkins-no-wizard
```
