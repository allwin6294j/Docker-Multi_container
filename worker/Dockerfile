FROM node:alpine
WORKDIR '/worker-server'
COPY package.json .
RUN npm install
COPY . . 
CMD ["npm", "run", "start"]