# Docker Test: build variables

I want to learn which environment variables are available on Docker Hub

See Docker image on Docker Hub: <https://hub.docker.com/r/tmaier/docker-test-build-variables/>

## Finding from [Build Details](https://hub.docker.com/r/tmaier/docker-test-build-variables/builds/)

```text
Step 2/2 : RUN printenv

 ---> Running in 7592197519b0

HOSTNAME=7592197519b0
SHLVL=1
HOME=/root
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
PWD=/

 ---> 75983b47bbf9
```

One may add more using the [hooks feature of Docker Hub](https://github.com/docker/hub-feedback/issues/508#issuecomment-240616319)

## Author

[Tobias L. Maier](https://tobiasmaier.info)
