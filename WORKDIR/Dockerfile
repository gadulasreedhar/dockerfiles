FROM almalinux:9
#RUN dnf install nginx -y
#CMD ["nginx","-g","daemon off;"]
RUN mkdir /tmp/docker
WORKDIR /tmp/docker
RUN pwd
RUN echo "Hello" > hello.txt
CMD ["sleep","100"]