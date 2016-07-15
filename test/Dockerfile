FROM node:4.4.3

RUN apt-get install libstdc++6

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY package.json /usr/src/app/
RUN npm install

COPY . /usr/src/app
CMD [ "npm", "test" ]


