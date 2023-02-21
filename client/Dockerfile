FROM node:18

WORKDIR /app/client

# Install app dependencies

COPY package*.json /app/client

RUN npm install

# Copy source code
COPY . .

# Envirenement variables
ENV PORT=5173