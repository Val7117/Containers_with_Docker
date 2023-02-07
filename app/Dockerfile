FROM node:19-alpine3.16

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=password

RUN mkdir -p /home/my-app

COPY ./my-app /home/my-app

CMD ["node", "/home/my-app/server.js"]
