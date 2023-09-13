FROM nginx

COPY wrapper.sh /

RUN chmod +x /wrapper.sh

COPY static.html /usr/share/nginx/html

EXPOSE 80

CMD ["./wrapper.sh"]
CMD ["nginx", "-g", "daemon off;"]



