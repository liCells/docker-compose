FROM n8nio/n8n:latest

USER root

# .......... yt-dlp .........
RUN apk update && \
    apk add --no-cache yt-dlp \
    curl && \
    rm -rf /var/cache/apk/*

RUN chown -R node:node /mnt

USER node

