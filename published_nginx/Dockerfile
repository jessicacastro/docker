FROM nginx:latest

COPY html /usr/share/nginx/html

# make nginx run and have the html folder
ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["nginx", "-g", "daemon off;"]