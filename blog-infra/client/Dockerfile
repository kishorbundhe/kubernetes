FROM node:alpine
WORKDIR /app
COPY package*.json ./
ENV CI=true
ENV PORT=3000
RUN npm install
COPY ./ ./
CMD ["npm", "start"]



