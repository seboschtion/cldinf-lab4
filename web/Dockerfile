FROM node:8.2

ENV API_HOST "api:5000"
ENV PORT 80

WORKDIR /var/app/src

COPY package.json .
RUN npm install

COPY . .
CMD npm start

EXPOSE 80
