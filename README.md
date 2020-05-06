## Discovery-Service

[![Build Status](https://travis-ci.com/devisv505/projectx-discovery-service.svg?branch=master)](https://travis-ci.com/devisv505/projectx-discovery-service)

```bash
 git checkout master
 git fetch && git reset --hard origin/master
 git merge --no-ff origin/SD-02

 mvn versions:set -DnewVersion=1.0 
 mvn clean install
 mvn versions:set -DnewVersion=1.1-SNAPSHOT 
 mvn clean install

 git add .
 git commit -m "up version"
 git push
```
