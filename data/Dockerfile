FROM debian

ADD ./api/ /opt

WORKDIR /opt/

RUN apt-get update -yq
RUN apt-get install -y python3-pip git
RUN pip3 install -r requirements.txt

ENTRYPOINT ["tail","-f","/dev/null"]
