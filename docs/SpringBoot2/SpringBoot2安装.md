# SpringBoot2介绍与开发准备

boot是引导的意思，也就是它的作用其实就是在于帮助开发者快速的搭建Spring框架，因此SpringBoot继承了Spring优秀的基因，在Spring中开发更为方便快捷。开发就像搭积木.

## 开发准备

Windows10/11 (笔者更推荐win10,感觉11还不是很好用)

IntelliJ IDEA 2024.2.0.1

科学上网工具 (非必选但推荐)

## 是否需要安装JDK什么配置?

暂时不需要配置环境变量,JAVA_HOME之类的,因为```jb公司```出品的IDE能和宇宙第一IDE visual studio 相媲美,完全可以靠鼠标点点点

## 下载 java 8

打开IDEA新建项目,下载一个1.8的JDK

![db6b7718b9f74c0aa628c8b7621905e0.png](/../vpstatic/images/20240902/db6b7718-b9f7-4c0a-a628-c8b7621905e0.png)

至此,开发环境已经配置完成,是不是和visual studio一样,无脑安装,点一下就行.下载完毕后窗口关闭就行了,可以先不用创建项目

## 创建项目,选择1.8

![61e6d2b8c484472f8ab0f23bbeca6f33.png](/../vpstatic/images/20240902/61e6d2b8-c484-472f-8ab0-f23bbeca6f33.png)

点击Create,会出现只包含pom.xml的空白项目

![d993798c33a9476595e838e461d564ad.png](/../vpstatic/images/20240902/d993798c-33a9-4765-95e8-38e461d564ad.png)

注意:可以通过 File -> Project Structure -> New Module 来创建其他项目,从而一个Idea包含多个project

![50fe507d3fcb4f3aa12054c3b0aaa6ec.png](/../vpstatic/images/20240902/50fe507d-3fcb-4f3a-a120-54c3b0aaa6ec.png)

创建完成后项目结构:

![058a0f5f61534f3f8185d5c064eca9f7.png](/../vpstatic/images/20240902/058a0f5f-6153-4f3f-8185-d5c064eca9f7.png)
