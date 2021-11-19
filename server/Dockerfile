FROM node:lts-alpine  
WORKDIR /server 
COPY package.json . 
RUN yarn install 
COPY . . 
EXPOSE 8000 
CMD ["node", "app.js"] 