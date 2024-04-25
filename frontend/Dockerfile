FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
COPY vite.config.js ./
RUN npm install
RUN npm install -g vite
COPY . .
EXPOSE 5173
CMD ["npm", "run", "dev"]
