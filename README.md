# nginxproxytel
proxy telegram nginx


server {
        listen 80;
        server_name _;
location /botxxx/ {
    proxy_set_header Host api.telegram.org;
    proxy_pass https://api.telegram.org/botxxx/;
}
}
