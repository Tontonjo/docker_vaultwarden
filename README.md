# Vaultwarden

## Tonton Jo - 2021


If you find this usefull, please consider supporting my work:  
- Join the community:
- 
[![C# Discord](https://badgen.net/discord/members/2NQskxZjfp/?label=Discord Tonton Jo)](https://discord.gg/2NQskxZjfp)  

 [Youtube Channel](http://youtube.com/channel/UCnED3K6K5FDUp-x_8rwpsZw?sub_confirmation=1)  
- <a href="https://www.buymeacoffee.com/tontonjo"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png"></a> <a href="https://www.infomaniak.com/goto/fr/home?utm_term=6151f412daf35"><img src="https://i.ibb.co/KjWSd95/banner-bleu.png"></a> </a> <a href="https://www.xvinlink.com/?a_fid=TontonJo"><img src="https://upload.wikimedia.org/wikipedia/en/thumb/7/79/ExpressVPN-logo.svg/261px-ExpressVPN-logo.svg.png"></a>  

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
