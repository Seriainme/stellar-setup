# stellar-setup
this project records my practice on setting up my blog on a new hexo theme of stellar .



问题集中在：

插入自定义的css 和 js 样式

blockquote引用字体样式设置 (待解决，用新的styl覆盖)


```
 inject:
  head:
    - <link rel="stylesheet" href="https://gcore.jsdelivr.net/gh/highlightjs/cdn-release@11.5.0/build/styles/atom-one-dark.min.css">

 script:
    - https://code.jquery.com/jquery-3.5.1.min.js
    - https://gitee.com/morel/blobemoji/raw/main/snowlike.js
    - https://raw.githubusercontent.com/Seriainme/blobemoji/main/snowlike.js
```

 
# todo

笔记功能 i can not figure it out 

侧边栏的美化

自定义小组件

zh en 字体的大小如何分开设置



# 大后期的需求

购买域名，注册七牛云图床

第二章的友链部分还没看

# what i learned
更改hexo的config.yml 文件来更改设置，比如站点的信息

文章添加<!-- more -->之前的内容为摘要，有加密的内容不能设置摘要，要把password置空

使用Spotify的插件来嵌入音乐