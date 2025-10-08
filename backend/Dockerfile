# backend/Dockerfile (Dev only)
FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=development
COPY . .
EXPOSE 5001
CMD ["npm", "run", "dev"]

