FROM adoptopenjdk/openjdk8:alpine

RUN apk update
RUN apk add bash curl git zip 
RUN curl -s "https://get.sdkman.io" | bash
RUN bash -c "source $HOME/.sdkman/bin/sdkman-init.sh"

