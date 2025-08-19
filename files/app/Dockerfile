FROM node:lts-alpine
WORKDIR /app
COPY package.json .
COPY . .
ENV KOTO=GABRIEL
RUN yarn install --production
CMD ["node", "src/index.js"]
EXPOSE 3000