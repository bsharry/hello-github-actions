FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN apt update
RUN apt install sl
RUN sl
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
