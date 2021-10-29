# Vaultwarden

## Tonton Jo - 2021
Join me on Youtube: https://www.youtube.com/c/tontonjo

If you find this usefull, please consider supporting my work:  
<a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a> <a href="https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35"><img src="https://i.ibb.co/KjWSd95/banner-bleu.png"></a> </a> <a href="https://www.xvinlink.com/?a_fid=TontonJo"><img src="https://cdn.vpninfo.dk/wp-content/uploads/2018/04/ExpressVPN-logo-1.png"></a>

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
