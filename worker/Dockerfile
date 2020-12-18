FROM node:alpine
WORKDIR /app
COPY worker/package.json /app
RUN npm install
COPY . /app
CMD ["npm", "run", "start"]