# frontend/Dockerfile
FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install || true

COPY . .

ENV PORT=3000
EXPOSE 3000

# If using Vite later, change to: npm run dev -- --host 0.0.0.0
CMD ["npm", "start"]
