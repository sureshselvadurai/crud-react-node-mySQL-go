FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8800

RUN npm install -g nodemon && chmod +x /usr/local/bin/nodemon
CMD ["npm", "start"]
