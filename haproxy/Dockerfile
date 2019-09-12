FROM haproxy:1.9.4-alpine

COPY ./haproxy.cfg /etc/haproxy/haproxy.cfg

CMD [ "haproxy", "-f", "/etc/haproxy/haproxy.cfg" ]
