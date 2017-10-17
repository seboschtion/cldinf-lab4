FROM node:8.2

ENV DB "postgres://postgres:b245005e8b3df99ac373f72240ba14df@db/postgres"
ENV PORT 5000

WORKDIR /var/app/src

COPY package.json .
RUN npm install

COPY . .
CMD npm start
