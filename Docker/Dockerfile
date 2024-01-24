# syntax=docker/dockerfile:1
FROM 'ubuntu'

RUN apt-get update
RUN apt-get install ca-certificates -y
RUN update-ca-certificates
WORKDIR /simple-mirror-k8s
RUN echo 'simple-mirror-k8s'
EXPOSE 7777
ADD build build

CMD ["./build/SimpleMirrorK8S.x86_64"]