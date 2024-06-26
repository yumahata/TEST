## Base Image
FROM nginx:1.25.0-alpine
## file 복사
COPY index.html /usr/share/nginx/html/index.html
COPY docker_logo.png /usr/share/nginx/html/docker_logo.png
## 80 port open
EXPOSE 80
## nginx를 백그라운드로 실행
CMD ["nginx", "-g", "daemon off;"]

