FROM node:20-alpine

WORKDIR /app
COPY . .

RUN npm install -g nodemon \
    && npm install -g ts-node 

EXPOSE 3000

CMD ["npm", "run", "dev"]