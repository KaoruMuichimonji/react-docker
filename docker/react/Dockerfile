FROM node:22-alpine

WORKDIR /app

COPY ../../frontend/package*json ./

RUN yarn install

COPY ../../frontend .

EXPOSE 5173

CMD ["yarn", "dev", "--host"]