FROM consul:1.8.3
EXPOSE 7500
EXPOSE 7300
EXPOSE 7301
ENV CONSUL_HTTP_ADDR=127.0.0.1:7500
CMD consul agent -config-file /etc/consul/consul.hcl