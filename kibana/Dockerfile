FROM kibana:latest

RUN apt-get update && apt-get install -y netcat

COPY startup.sh /tmp/startup.sh
RUN chmod +x /tmp/startup.sh

CMD ["/tmp/startup.sh"]
