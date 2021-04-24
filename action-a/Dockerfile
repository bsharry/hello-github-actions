FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN apt update
RUN apt install -y sl
RUN ls
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
