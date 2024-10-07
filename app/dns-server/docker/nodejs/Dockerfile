FROM node:20.18.0-alpine

RUN apk add yarn

COPY nodejs /var/app

WORKDIR /var/app

RUN yarn install

CMD ["yarn", "start"]
