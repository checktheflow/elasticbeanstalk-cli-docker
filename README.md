elasticbeanstalk-cli-docker
===========================
docker container containing aws elasticbeanstalk cli


Example Usage
-------------

```bash
docker run -it -v /path/to/credentials/.aws:/.aws -v $PWD/app-to-deploy:/src/app -w /src/app checktheflow/elasticbeanstalk-cli eb deploy
```
