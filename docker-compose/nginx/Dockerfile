FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf

COPY ./www/html /usr/share/nginx/html

ENTRYPOINT ["/docker-entrypoint.sh"]

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]
