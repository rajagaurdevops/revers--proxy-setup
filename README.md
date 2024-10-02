server {
    listen       80;
    server_name  domain-name;

     location / {
        proxy_pass http://localhost:port-number;
     }
}