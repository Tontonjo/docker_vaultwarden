# Vaultwarden

## Tonton Jo - 2021
Join me on Youtube: https://www.youtube.com/c/tontonjo

If you find this usefull, please consider supporting me trough <a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a> or <a href="https://www.buymeacoffee.com/tontonjo"><img src="https://i.ibb.co/KjWSd95/banner-bleu.png"></a> and Express VPN affiliated links :

## Sources: 
[Github Vaultwarden](https://github.com/dani-garcia/vaultwarden)  

## Information:  
Dont forget that you need a [Reverse Proxy](https://www.youtube.com/watch?v=7nyn_kfBAjk)!  

## Docker command:  
```shell
docker run -d \
--restart unless-stopped \
--name vaultwarden \
-v /path/to/data:/data/ \
-p 80:80 \
vaultwarden/server:latest
```
