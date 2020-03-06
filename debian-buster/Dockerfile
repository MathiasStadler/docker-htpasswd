FROM debian:buster-slim
ARG DEBIAN_FRONTEND=noninteractive
RUN apt update \
&& apt install -y -qq --no-install-recommends apache2-utils libapr1 libaprutil1 libexpat1 libgdbm6 libssl1.1 \
ENTRYPOINT ["/usr/bin/htpasswd","-Bbn"]
CMD []