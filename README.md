This repository is forked from Achrou/goindex-theme-acrou. To make it better serve for my requirements, I made some small changes so it can show some customized information. Most of Readme.md content is coming from original author. If you would like to know more options for this project, please visit original author's repository. 


# GoIndex-theme-acrou 
Combining the power of [Cloudflare Workers](https://workers.cloudflare.com/) and [Google Drive](https://www.google.com/drive/) will allow you to index you files on the browser on Cloudflare Workers.    

[go2index/index.js](https://github.com/51sec/goindex-theme-acrou/go2index) is the content of the Workers script.  

This theme's goindex is currently based on [yanzai/goindex](https://github.com/yanzai/goindex/)

[README](README.md) | [中文文档](README_zh.md)




## Demo  

51sec: [https://gd.51sec.org/](https://gd.51sec.org/) 

Collections : [https://chill.aicirou.workers.dev/](https://chill.aicirou.workers.dev/)

## Features

- [x] 👑 Page-level caching,browser forward and backward without reloading (MAC users have a better experience with the trackpad)
- [x] 🗂 Multi drive switching
- [x] 🔐 Http Basic Auth
- [x] 🎨 Grid view mode(File Preview)
- [x] 🎯 Paging load
- [x] 🌐 I18n(multi-language)
- [x] 🛠 Markdown/Html render (Maybe it can be your blog)
- [x] 🖥 Video Online(.vtt subtitle)
- [x] 🕹 Support for custom video player (API)
- [x] 🎧 Audio Online
- [x] 🚀 Faster speed


## Quick Deployment

1. Open any of the following links

   - https://install.achirou.workers.dev
   - https://goindex-quick-install.glitch.me
   - https://goindex-install.herokuapp.com

2. Auth and get the code  

3. Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)

## Deployment  

1. Open [Google Drive API](https://console.developers.google.com/apis/api/drive.googleapis.com/overview)
2. Create a [OAuth client ID](https://console.developers.google.com/apis/credentials/oauthclient)
3. Install [rclone](https://rclone.org/downloads/) software locally
4. Get `refresh_token ` with `rclone`
5. Download `index.js` in https://github.com/Aicirou/goindex-theme-acrou/tree/master/go2index and replace `client_id`,`client_secret`,`refresh_token` for what you just got.
6. Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/)






## Change log


51Sec's change:

API in the Cloudflare code :
Change from api: "https://api.jsonpop.cn/demo/blplyaer/?url=",
to : api: "https://sunpma.com/other/Player/?url=",

Another api : https://player.server.ci/?url=


"https://sunpma.com/other/Player/?url= " html5 online player does not support AVI. I am still trying to find a better html5 online player to replace this one. 

## Lisense

[MIT](LICENSE)

