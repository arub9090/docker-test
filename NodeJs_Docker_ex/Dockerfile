FROM node:14

WORKDIR /nodeJsApp

COPY package.json /nodeJsApp/

RUN npm install

COPY . /nodeJsApp/

EXPOSE 3000

CMD ["node", "server.js"]
