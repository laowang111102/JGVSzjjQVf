# 博客小程序+SSM

## 前言

在互联网高速发展的今天，博客已成为人们分享知识、经验，以及个人见解的重要平台。本项目是一个基于SSM框架和微信小程序的博客小程序，旨在帮助用户更便捷地发布和浏览博客内容。

## 内容介绍

本项目主要分为两个部分：后台管理和微信小程序端。后台管理主要负责对博客内容的增删改查操作，以及用户管理、评论管理等。微信小程序端则为用户提供了一个简洁、易用的阅读和互动环境。通过本项目的实施，您可以快速搭建一个属于自己的博客平台。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中一个简单的MyBatis查询操作的示例：

```java
// 在Mapper接口中定义方法
public interface BlogMapper {
    @Select("SELECT * FROM blog WHERE id = #{id}")
    Blog selectBlogById(@Param("id") int id);
}

// 在Service层调用Mapper接口
@Service
public class BlogService {
    @Autowired
    private BlogMapper blogMapper;

    public Blog getBlogById(int id) {
        return blogMapper.selectBlogById(id);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/328254/10/18969/189603/68c57ae4Fa6719c5d/4b1abe3e884a4249.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348668/13/2962/12234/68c57abbFaf40b5f8/71dcea5f48bd1355.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340602/24/10440/38457/68c57abcF059d41a1/4aef751592b47b49.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348943/5/3059/151362/68c57abcFfa731951/fa7f42d389f1c715.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336239/35/8917/45707/68c57abcFfc8fc0f4/b6fdd828595c93cf.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/343988/16/2952/12402/68c57abcF0b064f78/fc9c910ee61e21c4.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349517/21/2971/16413/68c57abdFd965c775/ed491c7bef52ac5e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348908/17/2900/48610/68c57abdF34599136/422929d860833b33.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/338481/28/10355/21541/68c57abdF8830886e/7b2221a90f382b6a.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/330471/28/12797/30380/68c57abdF02376821/8652e7bb8125de1f.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
