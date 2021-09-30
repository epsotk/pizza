FROM node:12.18.0

WORKDIR /app

COPY package.json .
COPY yarn.lock .

RUN yarn

CMD yarn start