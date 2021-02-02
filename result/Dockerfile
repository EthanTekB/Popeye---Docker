FROM node:12-alpine
WORKDIR /result
COPY . /result
RUN npm install
EXPOSE 80
ENV NOM ethan
CMD ["node", "server.js"]