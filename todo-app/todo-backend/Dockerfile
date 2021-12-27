# in terminal run: docker run -p 3000:3000 todo-backend
# visit:  http://localhost:3000/

FROM node:16

USER node
  
WORKDIR /usr/src/app

COPY . .

RUN npm ci --only-production

CMD npm start