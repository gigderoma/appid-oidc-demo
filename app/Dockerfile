FROM icr.io/codeengine/node:12-alpine
RUN npm install --save express express-session passport@0.5.2 log4js pug ibmcloud-appid
COPY ./ .
EXPOSE 8080
CMD [ "node", "web-app-sample-server.js" ]
