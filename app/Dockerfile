FROM node:12-alpine
WORKDIR /app
COPY . .
RUN yarn install --productiojn
CMD ["node", "src/index.js"]