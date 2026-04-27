FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
RUN exit 1
COPY . .
EXPOSE 12345
CMD ["node", "app.js"]
