FROM ubuntu:latest

RUN apt-get update && apt-get install -y cowsay && ln -s /usr/games/cowsay /usr/bin/cowsay
# COPY docker.cow /usr/share/cowsay/cows/docker.cow

# ENTRYPOINT ["cowsay","docker"]
CMD ["cowsay","docker"]