sever{
listen  80;
sever_name domain name;

location /{
    proxy_pass http://localhost:port name;

   }
}