FROM node:10
# alpine -> error
# alpine don't have files for npm

COPY ./ ./

RUN npm install

CMD ["node", "server.js"]