FROM node:alpine
WORKDIR /usr/diot/subscriber
COPY subscriber.js /usr/diot/subscriber
COPY payload.json /usr/diot/subscriber
RUN npm install mqtt
CMD ["node","subscriber.js"]
