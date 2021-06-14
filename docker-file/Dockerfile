#dockerfile => docker imsge

#กำหนด image
FROM node:alpine 

WORKDIR /usr/app


#Entry Point
COPY ./package.json ./
#copy file [เริ่่มต้น] => [สิ้นสุด] เอาไฟล์ทั้งหมดไป

RUN  npm install
COPY ./ ./

#หลังจาก install แล้วก็จะทำการ เริ่มโปรแกรม
CMD [ "npm", "start" ]