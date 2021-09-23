FROM node:14-alpine

RUN mkdir -p /var/www/html

WORKDIR /var/www/html

COPY /app/package*.json /var/www/html/

RUN yarn

EXPOSE 3000

CMD yarn dev