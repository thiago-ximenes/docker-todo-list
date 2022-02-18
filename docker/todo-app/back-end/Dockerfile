FROM node:14-alpine AS build
WORKDIR /app
EXPOSE 3001
COPY . .
ADD node_modules.tar.gz .
CMD ["npm", "start"]
