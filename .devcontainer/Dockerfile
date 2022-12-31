FROM adoptopenjdk/openjdk11

RUN apt-get update
RUN apt-get -y install curl
RUN apt-get -y install zip
RUN apt-get -y install git
RUN apt-get -y install mesa-utils
RUN curl -s "https://get.sdkman.io" | bash
RUN echo ". $HOME/.sdkman/bin/sdkman-init.sh; sdk install gradle 7.5.1" | bash
WORKDIR /usr/project