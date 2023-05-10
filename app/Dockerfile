FROM icr.io/codeengine/node:12-alpine
RUN npm install --save express@4.18.2  express-session@1.17.3 passport@0.5.2 log4js pug ibmcloud-appid
COPY ./ .
EXPOSE 8080
CMD [ "node", "server.js" ]
