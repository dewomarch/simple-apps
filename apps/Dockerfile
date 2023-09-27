
#image
FROM node:18.16.0

#directory kerja
WORKDIR /apps

#copy file dari host linux ke work directory
ADD . /apps

#install module 

RUN npm install 

# menjalankan perintah saat containar jalan

CMD npm start

#expose port
EXPOSE 3000