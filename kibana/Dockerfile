FROM kibana:latest

ENV http_proxy http://len980:Password0116@10.37.135.39:8099/
ENV https_proxy http://len980:Password0116@10.37.135.39:8099/

RUN apt-get update && apt-get install -y netcat

COPY startup.sh /tmp/startup.sh
RUN chmod +x /tmp/startup.sh

CMD ["/tmp/startup.sh"]
