FROM node:alpine
WORKDIR '/express-server'
COPY package.json .
RUN npm install
COPY . . 
CMD ["npm", "run", "start"]