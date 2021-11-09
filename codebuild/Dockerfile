FROM nginx:1.17.10

# Software's Installation
RUN set -eux; \
    apt-get update; \
    apt-get install -y --no-install-recommends

CMD ["nginx"]

EXPOSE 80 443
