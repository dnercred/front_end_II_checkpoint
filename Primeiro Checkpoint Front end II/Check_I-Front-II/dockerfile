# FROM httpd
FROM nginx

# Atualizando o repositório do Linux
RUN apt update


# COPY . /usr/local/apache2/htdocs/
COPY . /usr/share/nginx/html



# para testar
# docker build --tag checkpoint-frontend
# docker container run -d -p 80:80 checkpoint-frontend