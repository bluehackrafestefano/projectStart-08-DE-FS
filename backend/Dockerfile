FROM node:18-alpine3.20

WORKDIR /backend

COPY . .

RUN mkdir -p logs
RUN mkdir -p upload

RUN npm install

EXPOSE 8000

CMD [ "npm", "start" ]
