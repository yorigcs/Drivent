FROM node
WORKDIR /usr/src/drivent
COPY ./package*.json ./
COPY ./.husky ./
RUN npm install --legacy-peer-deps
COPY . .