FROM busybox as builder
COPY page.html page.html

FROM nginx
COPY --from=builder page.html /usr/share/nginx/html/page.html 

