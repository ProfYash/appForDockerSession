FROM node:13-alpine
RUN mkdir /home/app
WORKDIR /home/app
COPY ./ ./
RUN npm install
CMD ["node", "server.js"]