FROM  node:10.12.0-slim

WORKDIR /client
COPY . .
RUN yarn install --ignore-engines
CMD ["yarn", "start"]
EXPOSE 3000
