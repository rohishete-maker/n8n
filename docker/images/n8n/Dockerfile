FROM n8nio/n8n:latest

USER root

RUN apt-get update && apt-get install -y curl

WORKDIR /home/node

EXPOSE 5678

CMD ["n8n"]
