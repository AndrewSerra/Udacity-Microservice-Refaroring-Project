FROM node:12
WORKDIR /usr/src/app
COPY package*.json ./

#RUN npm install
RUN npm ci

COPY . .
EXPOSE 3001
CMD ["npm", "run", "prod"]
