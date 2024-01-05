FROM node:18-alpine
WORKDIR /app
COPY .. .
RUN npm install
RUN npm i sqlite3
CMD ["npm", "start"]
EXPOSE 5000