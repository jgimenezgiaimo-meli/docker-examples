FROM nginx:alpine

WORKDIR /usr/src/app

COPY ./conf/app.conf /etc/nginx/nginx.conf

# Copy from the stahg 1
COPY ./src /usr/src/app

EXPOSE 3000 80

ENTRYPOINT ["nginx", "-g", "daemon off;"]
