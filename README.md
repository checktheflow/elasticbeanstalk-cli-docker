elasticbeanstalk-cli-docker
===========================
docker container containing aws elasticbeanstalk cli


Example Usage
-------------

```bash
docker run -it -v /path/to/credentials/.aws:/.aws -v $PWD/app-to-deploy:/src/app -w /src/app checktheflow/elasticbeanstalk-cli eb init
```

Links
-----

- [GitHub](https://github.com/checktheflow/elasticbeanstalk-cli-docker)
- [elasticbeanstalk-cli](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html)
- [elastic beanstalk](https://aws.amazon.com/elasticbeanstalk/)


License
-------

Released under the MIT License.
