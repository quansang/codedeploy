FROM nginx:1.17.10

# Software's Installation
RUN set -eux; \
    apt-get update; \
    apt-get install -y --no-install-recommends

RUN echo "deployment-1" > /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80 443
