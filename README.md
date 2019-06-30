# nginx-course

start the nginx server
```bash
docker run --name nginx -d -p 80:80 nginx
```

get inside the nginx container
```bash
docker exec -it nginx bash
```

get inside the nginx config folder
```bash
cd /etc/nginx
```

for getting the live logs
```bash
docker logs -f nginx
```

nginx config file syntax check
```bash
nginx -t
```

