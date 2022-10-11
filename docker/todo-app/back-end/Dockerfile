
FROM node:14

WORKDIR /todo-app/back-end


ADD node_modules.tar.gz .
# COPY package*.json .
# RUN npm install

COPY . .
EXPOSE 3001

ENTRYPOINT ["npm", "start"]