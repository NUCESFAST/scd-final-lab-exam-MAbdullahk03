FROM node:20-alpine

WORKDIR /21I-1176_backend

COPY package*.json ./

RUN npm install

COPY . .

# my rollnumber: 1176 , so performed two circular left shift on it (result: 7611) 
EXPOSE 7612

CMD ["node", "index.js"]
