FROM awx_web:1.0.0.588

RUN sed -i 's/localhost/127.0.0.1/g' /etc/nginx/nginx.conf && \
    pip install netaddr jmespath