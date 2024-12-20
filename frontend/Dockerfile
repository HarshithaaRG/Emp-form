FROM node:20
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm","start"]

#1. docker build -t frontend:version1 .  -> image_name:tag_name -> . =root dir=>IMAGE BUILDING
#2. docker run -p 8067:3000 frontend:version1 ->PORT MAPPING TO DOCKER PORT TO REACT PORT => CONTAINERISING
#3. docker hub -> login -> new repo
#4. terminal login -> two commands to build tag and push image
#5. docker tag frontend:version1 harshithaarg/empform:version1
#6. docker push harshithaarg/empform:version1
