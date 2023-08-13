FROM node:14.17.0
WORKDIR /frontend
COPY ../frontend/package.json /frontend
RUN npm install
COPY ../frontend/. .
CMD npm start
EXPOSE 3000

