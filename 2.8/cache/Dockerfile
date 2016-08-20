FROM redis:2.8
MAINTAINER Allan MacGregor <amacgregor@allanmacgregor.com>

COPY redis.conf /usr/local/etc/redis/redis.conf
RUN mkdir -p /var/log/redis/ && chown -R redis:redis /var/log/redis

EXPOSE 6380
CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]
