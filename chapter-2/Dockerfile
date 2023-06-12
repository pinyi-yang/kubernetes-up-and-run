FROM node:16

WORKDIR /user/src/app

COPY package*.json ./
RUN npm install
RUN npm install express

COPY . .

CMD ["npm", "start"]