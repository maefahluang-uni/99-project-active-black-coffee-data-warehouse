FROM node:20-alpine

RUN mkdir -p /usr/src/nuxt-app
WORKDIR /usr/src/nuxt-app
COPY . .

ARG BASE_URL=http://localhost:1337
ARG NUXT_PORT=3000
ARG NUXT_HOST=0.0.0.0


ENV BASE_URL=${BASE_URL}
ENV NUXT_PORT=${NUXT_PORT}
ENV NUXT_HOST=${NUXT_HOST}

RUN yarn install && yarn build

EXPOSE 3000 

ENTRYPOINT ["node", ".output/server/index.mjs"]