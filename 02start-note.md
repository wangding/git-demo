# 快速上手

## 第零步，环境准备

- 启动 XShell  
- 连接到 linux 虚拟机  
- 安装 Git 和 vim  
- 配置 Git 和 vim 的参数  

## 第一步，创建项目

- 在 GitHub 上创建空仓库：jekyll-demo  
- 在该仓库上启用 GitHub pages 设置  
- 在自己的电脑上，克隆该仓库  

## 第二步，创建设置文件

- 在项目根目录下，建立一个名为 \_config.yml 的文本文件

目录结构变成：

    　　/jekyll_demo
    　　　　|--　_config.yml

## 第三步，创建模板文件

- 在项目根目录下，创建一个 \_layouts目录，用于存放模板文件  
- 在该目录下，创建一个 default.html 文件，作为 Blog 的默认模板  

目录结构变成：

    　　/jekyll_demo
    　　　　|--　_config.yml
    　　　　|--　_layouts
    　　　　|　　　|--　default.html

## 第四步，创建文章

- 在项目根目录，创建一个 \_posts 目录，用于存放 blog 文章  

目录结构变成：

    　　/jekyll_demo
    　　　　|--　_config.yml
    　　　　|--　_layouts
    　　　　|　　　|--　default.html
    　　　　|--　_posts
    　　　　|　　　|--　2017-07-04-hello-world.html

## 第五步，创建首页

- 在项目根目录，创建一个 index.html 文件  

目录结构变成：

    　　/jekyll_demo
    　　　　|--　_config.yml
    　　　　|--　_layouts
    　　　　|　　　|--　default.html

    　　　　|　　　|--　2017-07-04-hello-world.html
    　　　　|--　index.html

## 第六步，发布内容

- 把所有内容加入本地 git 库  
- 把本地 git 仓库的内容推送到远程仓库  
- 通过浏览器访问这个博客  

## 第七步，绑定域名

- 在域名管理平台添加域名的 CNAME 记录
- 在 GitHub 仓库中增加 CNAME 文本文件
- 用新的域名访问博客系统

