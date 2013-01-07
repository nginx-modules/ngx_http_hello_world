# nginx_http_hello_world

Hello, World with nginx

```
location ~ /hello_world$ {
    hello_world;
}
```

```
$ curl -l "http://127.0.0.1:80/hello_world"
<!DOCTYPE html>
<html>
<head>
<title>Hello, World with nginx!</title>
</head>
<body>
<p>Hello, World!</p></body>
</html>
$
```
