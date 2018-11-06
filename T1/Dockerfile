# Dockerfile WWW-sovellukset -kurssin viikon 7 tehtäviin 
# Apua katsottu https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
FROM node:8

WORKDIR /app

COPY ./express-locallibrary-tutorial/package*.json ./

RUN npm install

COPY ./express-locallibrary-tutorial/ .

EXPOSE 8080

CMD ["npm", "start"]
