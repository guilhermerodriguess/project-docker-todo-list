FROM alpine:3.14
WORKDIR /app
EXPOSE 3001
ADD ./node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
