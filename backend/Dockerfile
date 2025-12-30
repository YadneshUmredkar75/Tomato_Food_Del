# 1. Use Node.js image
FROM node:20

# 2. Set working directory
WORKDIR /app

# 3. Copy package files
COPY package*.json ./

# 4. Install dependencies
RUN npm install

# 5. Copy all backend files
COPY . .

# 6. Expose backend port
EXPOSE 4000

# 7. Start backend using nodemon
CMD ["npm", "run", "server"]
