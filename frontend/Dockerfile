
# Stage 1: build
FROM node:14 AS development

WORKDIR /nikita/frontend/src/app

RUN npm install
RUN npm install -g @angular/cli@12.0.0

COPY . .

RUN npm run build

EXPOSE 4200
