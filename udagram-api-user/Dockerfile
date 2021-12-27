FROM node:12.6.0
#Create the work directory
WORKDIR /usr/src/app

COPY package.json ./
RUN npm install
RUN npm install typescript 
RUN npm install bcrypt 

COPY . .
EXPOSE 8080
CMD ["npm", "run", "prod"]