FROM node

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . . 

EXPOSE 4000
CMD ["npm", "start"]

# docker images to show current images 
# docker rmi = delete the image in the docker CLI 
# docker run -p 4000:4000 roblopez/simple-backend
# docker ps is used to list the container 
# docker stop dfee - stop the container image 
# docker kill - will kill the container 
# docker pull / push to pull and push to the repository 
