FROM node:16.13.2-alpine3.14

EXPOSE 3000
ENV HOST 0.0.0.0

# コマンド実行
RUN apk update && \
    # apk add git && \
    npm install -g @vue/cli nuxt create-nuxt-app
