# un

```
unikraft run --metro=sin -m 512MiB -p 443:3000/http+tls -e KOMARI_SERVER="https://xxxxxxx" -e KOMARI_TOKEN="xxxxxxxx" -e PORT="3000" -e TLS="false" -e SHOW_LOG="1" --scale-to-zero policy=on,cooldown-time=60000 --image ghcr.io/fnosnas/ws-un:latest
```

替换为 --metro=sin    

sin   是选择地区
