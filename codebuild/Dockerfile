FROM nginx:1.18.10

# Software's Installation
RUN set -eux; \
    apt-get update; \
    apt-get install -y --no-install-recommends

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80 443
