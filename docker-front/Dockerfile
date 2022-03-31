FROM nginx:1.16.1
RUN mkdir /app
COPY ./cps /app/cps/
COPY nginx.conf /
CMD ["/usr/sbin/nginx","-c","/nginx.conf","-g","daemon off;"]
