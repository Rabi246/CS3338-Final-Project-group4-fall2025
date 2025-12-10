# Frontend Dockerfile (placeholder until React app is built)

FROM node:20-alpine

WORKDIR /app

# If package.json exists later, this will install dependencies
COPY package*.json ./
RUN npm install || true

COPY . .

EXPOSE 3000

# Placeholder command (team will update if using Vite or CRA)
CMD ["npm", "start"]
