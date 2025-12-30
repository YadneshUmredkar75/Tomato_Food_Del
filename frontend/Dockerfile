# 1. Use Node.js
FROM node:20

# 2. Set working directory
WORKDIR /app

# 3. Copy package files
COPY package*.json ./

# 4. Install dependencies
RUN npm install

# 5. Copy all frontend files
COPY . .

# 6. Expose Vite port
EXPOSE 5173

# 7. Run Vite dev server
CMD ["npm", "run", "dev", "--", "--host"]
