FROM node:20
WORKDIR /quizza-server
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
