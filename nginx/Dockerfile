FROM debian:bullseye-slim
RUN apt-get update
RUN apt-get install -y nginx

EXPOSE 80

STOPSIGNAL SIGQUIT

CMD ["nginx"]
