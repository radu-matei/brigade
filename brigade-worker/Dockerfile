FROM node:8-alpine

WORKDIR /home/src
COPY brigade-worker/ /home/src/
RUN npm run-script build

CMD npm test
