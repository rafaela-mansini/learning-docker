#image that we want use
FROM node:14

# container work directory
WORKDIR /app

# copy our the package.json in working directory
COPY package.json .

# run the command to install add all dependencies needed
RUN npm install

# copy the rest of the code to work directory
COPY . .

# expose the port 3000 from outside
EXPOSE 3000

# execute the app.mjs with the node command
CMD ["node", "app.mjs"]