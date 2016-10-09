FROM ubuntu:14.04
MAINTAINER Ray Terrill, rayjohnterrill@gmail.com

RUN apt-get update && apt-get upgrade -y && apt-get install -y python2.7 python2.7-dev python-pip git libssl-dev libffi-dev libjpeg-dev && DEBIAN_FRONTEND=noninteractive apt-get install -y mysql-server libmysqlclient-dev && apt-get autoremove && apt-get clean

RUN git clone https://github.com/cmazuc/scarfage.git && cd scarfage && pip install -r requirements.txt

EXPOSE 5000/tcp
