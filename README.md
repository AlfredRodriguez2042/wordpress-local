## instal mkcert
```
 mkcert -install myapp.local
 mv *.pem certs/

```

## hosts /etc/hots
```
127.0.0.1 myapp.local.com or myapp.local
```
## run 
```
docker-compose up -d
```

## open browser
```
https://myapp.local.com/wp-admin/install.php
```