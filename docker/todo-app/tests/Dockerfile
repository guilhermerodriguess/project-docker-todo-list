FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
ADD node_modules.tar.gz .
EXPOSE 3000
COPY . . 
CMD ["npm", "test"]