FROM node

RUN mkdir /usr/src/app
WORKDIR /usr/src/app

ENV PATH /usr/src/app/node_modules/.bin:$PATH

COPY package*.json /usr/src/app

RUN npm install

COPY . /usr/src/app 

EXPOSE 4000
CMD ["npm", "start"]

# docker images to show current images 
# docker rmi = delete the image in the docker CLI 
# docker run -p 4000:4000 roblopez/simple-backend
# docker ps is used to list the container 
# docker stop dfee - stop the container image 
# docker kill - will kill the container 
# docker pull / push to pull and push to the repository 
