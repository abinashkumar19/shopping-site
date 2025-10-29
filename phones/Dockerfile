FROM nginx:latest
WORKDIR /usr/share/nginx/html
COPY phones.html index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
