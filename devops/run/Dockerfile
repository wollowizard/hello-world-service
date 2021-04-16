FROM node:12
WORKDIR /usr/app
COPY ./dist/ ./dist
COPY ./package*.json ./
RUN echo -----------------run src--------------
CMD ["npm", "start"]
