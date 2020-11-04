FROM node:10

WORKDIR /usr/src/omnistack

COPY package.json .

RUN npm install --quiet

# Install Expo CLI
RUN npm install --global expo-cli

COPY . .
