# hugo
hugo demo test

测试使用golang制作的静态网站生成工具 hugo

1.生成网站目录
hugo new site  目录名称

2.本地启动查看静态页面效果

hugo server --theme=主题名称  

3.发布静态站点
hugo --theme=hyde --baseUrl="https://2676583711.github.io/hugo/" --buildDrafts
会在网站目录下面生成新的目录：public 目录，这个目录下面的东西发布出去就是完整网站
