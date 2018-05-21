FROM guidowb/tile-pipeline

RUN apk add --no-cache curl wget ca-certificates bash util-linux
RUN \
  curl -v -L -o /usr/bin/dumb-init https://github.com/Yelp/dumb-init/releases/download/v1.2.0/dumb-init_1.2.0_amd64 && \
  chmod +x /usr/bin/dumb-init
RUN pip install tile-generator
