FROM icr.io/codeengine/node:12-alpine
RUN npm install
RUN npm install --save express express-session passport log4js pug
RUN npm install --save ibmcloud-appid
COPY server.js .
COPY public public
EXPOSE 8080
CMD [ "node", "server.js" ]
