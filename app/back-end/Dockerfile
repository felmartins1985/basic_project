FROM node:16.14-alpine
WORKDIR /app-backend
COPY package* ./
RUN npm install
COPY . .
RUN npm run prestart
CMD ["npm", "run","dev"]
EXPOSE 3001