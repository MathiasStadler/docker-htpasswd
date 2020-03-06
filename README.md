# docker-htpasswd
create htpasswd  via docker

## based on
- https://github.com/fvigotti/docker-images/blob/master/src/utils/apacheutils/src/Dockerfile
- https://github.com/xmartlabs/docker-htpasswd


## build

```bash
git clone https://github.com/MathiasStadler/docker-htpasswd/edit/master/README.md
docker build -t docker-htpasswd -f docker-htpasswd/Dockerfile .
```

## usage

```bash
docker run --rm -it docker-htpasswd <username> <password> >htpasswd
```
