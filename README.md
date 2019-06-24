# nginx-reverse-proxy

create and configure nginx for reverse proxy

required :

```nginx >= 1.14.0```

run this command for install nginx :

```$ apt-get install nginx -y```

include files "```nginx.conf```" and "```proxy.conf```" in "```/etc/nginx/```"

modify nginx config file in "```/etc/nginx/```" at line "```proxy_pass```" with you ip or localhost

restart nginx service with :

```systemctl restart nginx```