FROM ubuntu:25.10
RUN apt update -y && apt install nginx -y
COPY drinking-water-website-template /var/www/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
