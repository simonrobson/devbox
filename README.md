(OS X-focused) scripts to run development infrastructure via [docker](http://www.docker.com) / boot2docker.

Make sure that you have initialized [boot2docker](http://boot2docker.io/) and that boot2docker is running.

Then run this command to start a postgres container:
```
# ./run-pg
```

This will assign a data container for postgres (devbox-pg-data) and fire up a postgres container (devbox-pg) mapped to port 5432 on the boot2docker host.


