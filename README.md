Scripts to run development infrastructure via docker / boot2docker.

Make sure that you have initialized boot2docker and that boot2docker is running.

Then run this command to start a postgres:
```
# ./run-pg
```

This will assign a data container for postgres (devbox-pg-data) and fire up a postgres container mapped to port 5432 on the boot2docker host.


