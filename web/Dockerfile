FROM ansible/awx_web:1.0.1.10

USER root

RUN sed -i 's/localhost/127.0.0.1/g' /etc/nginx/nginx.conf && \
    pip install netaddr jmespath

USER 1000
