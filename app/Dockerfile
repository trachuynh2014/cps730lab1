FROM nginx:1.23.3
WORKDIR /app
COPY . .
RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y nodejs \
    npm
CMD ["node", "src/index.js"]