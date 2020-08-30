FROM node:current-slim
COPY package*.json ./
RUN npm install
EXPOSE 8080
COPY app.js .
CMD [ "npm", "start" ]