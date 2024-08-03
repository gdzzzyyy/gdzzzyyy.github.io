---
layout: post
title: instagram
date: 2024-08-03 13:25:30
title: "相册"
noDate: "true"
---
<div class="instagram" data-client-id="956dd096b6e5496aba6662165b9b8443" data-user-id="438522285">
    <a href="https://www.instagram.com/" target="_blank" class="open-ins">图片来自instagram，正在加载中…</a>
</div>
<script src="/js/jquery.lazyload.js"></script>
<script src="/js/instagram.js"></script>
```
注意其中的**data-client-id**属性，是你instagram上的client-id(不是用户id)。                    
具体可到[instagram-manage](http://instagram.com/developer/clients/manage/)网站上去获得。                       
**data-user-id**属性，需要到[lookup-user-id](http://jelled.com/instagram/lookup-user-id#)查找并填写。                          

有了这两个参数，就可以获取到instagram的图片了。                        

如遇到疑问，也可以参考这篇文章[《instagram图片拉取小经验》](http://litten.github.io/2014/03/03/instagram-api-ex/)并留言。

另外，Yilia实现了图片异常处理，会将instagram图片的cdn路径替换成源服务器路径。因而你不必担心图片在天朝被墙的情况。