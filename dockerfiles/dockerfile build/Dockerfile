FROM node:13
WORKDIR /app
RUN npm install -g gatsby-cli
RUN gatsby new my-gatsby-project https://github.com/santosfrancisco/gatsby-starter-cv
WORKDIR /app/my-gatsby-project 
CMD  ["gatsby","build"]
