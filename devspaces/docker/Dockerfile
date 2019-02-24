FROM ubuntu:18.04

LABEL description="This file generates a docker image containing everything needed to build SQLiteBrowser application."

WORKDIR /data

RUN apt-get update && apt-get install -y qttools5-dev qt5-default build-essential cmake libsqlite3-dev && \
    apt-get clean

CMD [tail -f /dev/null]
