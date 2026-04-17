FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
RUN exit 1
COPY . .
EXPOSE 5000
CMD ["node", "app.js"]
