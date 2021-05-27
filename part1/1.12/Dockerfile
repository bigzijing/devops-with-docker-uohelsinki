FROM node

WORKDIR /usr/src/app

COPY example-frontend/ .

EXPOSE 5000

RUN curl -sL https://deb.nodesource.com/setup_14.x | bash 
RUN apt install -y nodejs
RUN npm install

RUN npm run build
RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]
