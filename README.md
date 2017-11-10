# KIXEYE Test Application

This application is provided as a dependency for the [DevOps challenge](../../challenges/deployment.md).

## Dependencies

* Java Runtime Environment: `version 1.8.0_121`
* Redis: `redis.local:6379`
* Logging: local file system at `/var/log/kixeye/testapp.log`

## Run

the following will run the application (replacing the path to the test jar with an actual path):
`java -cp path/to/application/jar/testapp.jar kixeye.testapp.Main`