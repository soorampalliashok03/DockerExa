from almalinux
run dnf install nginx -y
run rm -rf /usr/share/nginx/html/index.html
copy TestumITS /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]