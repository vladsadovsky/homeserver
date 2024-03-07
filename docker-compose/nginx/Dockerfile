FROM nginx:alpine

#COPY nginx.conf /etc/nginx/nginx.conf

COPY ./www /var/www

ENTRYPOINT ["/docker-entrypoint.sh"]

STOPSIGNAL SIGQUIT

CMD ["nginx", "-g", "daemon off;"]
