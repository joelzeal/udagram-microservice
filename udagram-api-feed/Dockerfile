FROM node:12
#Create the work directory
WORKDIR /usr/src/app

COPY package*.json ./
RUN npm ci

COPY . .
EXPOSE 8080
CMD ["npm", "run", "prod"]



