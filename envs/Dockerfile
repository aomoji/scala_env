FROM hseeberger/scala-sbt:8u222_1.3.5_2.13.1

USER root

RUN apt-get update && apt-get install -y --no-install-recommends \
    zsh \
    && apt-get clean && rm -rf /var/lib/apt/lists/*

RUN mkdir -p /home/sandbox

# docker-compose run --rm scala_sandbox /bin/zsh