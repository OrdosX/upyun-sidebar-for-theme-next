# upyun-sidebar-for-theme-next
这是我仿照NexT原生友链模块制作的又拍云联盟侧边栏。所用图片由又拍云官网原图修改而来，减少高度以避免侧边栏出现滚动条。

## 使用说明
+ 替换 ` <hexo_path>/themes/next/layout/_custom ` 目录下的 ` sidebar.swig ` 为本仓库中的 ` sidebar.swig `

+ 下载 ` upyun.png ` 到目录  ` <hexo_path>/themes/next/source/images ` 中

+ 打开 ` <hexo_path>/themes/next/_config.yml ` ，找到 ` custom_file_path ` 部分，改成这样。注意取消#号：

```yml
custom_file_path:
  # Default paths: layout/_custom/*
  #head: source/_data/head.swig
  #header: source/_data/header.swig
  sidebar: themes/next/layout/_custom/sidebar.swig
```

以上提到的 `<hexo_path>` 指你执行 `hexo g` 等命令时所在的目录。