SoapUI 5.2.1 docker
============

* SoapUI is a free and open source cross-platform Functional Testing solution. http://www.soapui.org/

* Support Chinese

# RUN

* testrunner

```
docker run --rm -it -v ~:/var/home jmcn/soapui-docker -l -c "testrunner.sh -Dfile.encoding=UTF-8 -I -j -f/var/home/report/ /var/home/soapui-project.xml"
```

* mockservicerunner

```
docker run --rm -it -v ~:/var/home jmcn/soapui-docker -l -c "mockservicerunner.sh /var/home/soapui-project.xml"
```

