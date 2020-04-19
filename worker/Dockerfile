FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .
# scripts defined in package.json file
CMD ["npm", "run", "start"]
