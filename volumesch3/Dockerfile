FROM node:14

WORKDIR /nodeVolume

COPY package.json /nodeVolume/

RUN npm install 

COPY . /nodeVolume/

EXPOSE 80

CMD ["node", "server.js"]