# 前言

欢迎来到本仓库，这里为您分享一款基于Java技术的实战项目——水果蔬菜商城。该项目是一款结合了Spring Boot、Vue等前端技术的电子商务平台，能够帮助您掌握Java开发的全过程。以下是项目详细介绍，希望对您有所帮助。

## 内容介绍

水果蔬菜商城是一款以线上销售水果和蔬菜为主体的电子商务平台。通过使用Java语言和Spring Boot框架，实现了商品展示、分类、搜索、购物车、订单管理等功能。前端采用Vue、JS和CSS3技术，使得页面美观、响应速度快，用户体验良好。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中一个简单的Java代码示例，展示了如何实现商品分类查询：

```java
@RestController
@RequestMapping("/category")
public class CategoryController {

    @Autowired
    private CategoryService categoryService;

    @GetMapping("/list")
    public ResponseEntity<List<Category>> list() {
        List<Category> categories = categoryService.list();
        return ResponseEntity.ok(categories);
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

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/315731/28/26727/83654/689f0746Fb7484a30/435cd258ceefdca3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328301/11/4887/17344/689f0720Fa477258e/e7bd4d7e0794e5e7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/308706/7/27052/38432/689f0726F962422cb/04bf43a69c83ca1b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327366/19/5001/20062/689f0726F9c6a0e1b/571bbdf4e23c7d1c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/314066/17/26884/65430/689f0727F9b9267e0/b1a7cc3b7da96d44.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/308805/29/26930/105843/689f0729Facc2d162/4c76c9df394723ee.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/291241/21/22497/108953/689f0728F20ecc1e6/479fd08cbc269f7a.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/316769/39/25345/122119/689f072aFf4669602/ee1746829603decf.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/293226/4/19404/34109/689f072aFc1f448d8/5705c353aa78f2ab.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/313447/8/26354/34648/689f072bF2e26ea51/8dc15ce8497bfa75.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
