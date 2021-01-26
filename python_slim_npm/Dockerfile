FROM python:3.9-slim-buster

RUN apt-get update
# RUN apt-get install gcc -y
RUN apt-get install npm -y
RUN npm install npm@latest -g

RUN npm install bulma --save-dev -g --unsafe-perm
RUN npm install css-loader --save-dev -g --unsafe-perm
RUN npm install extract-text-webpack-plugin@next --save-dev -g --unsafe-perm
RUN npm install mini-css-extract-plugin --save-dev -g --unsafe-perm
RUN npm install node-sass --save-dev -g --unsafe-perm
RUN npm install sass-loader --save-dev -g --unsafe-perm
RUN npm install style-loader --save-dev -g --unsafe-perm
RUN npm install webpack --save-dev -g --unsafe-perm
RUN npm install webpack-cli --save-dev -g --unsafe-perm
