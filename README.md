# 前言

欢迎来到基于SSM的宿舍维修服务项目！此项目旨在为高校宿舍维修提供一个便捷、高效的平台，通过整合Spring、Spring MVC和MyBatis等主流技术，实现了一套完善的宿舍维修管理系统。以下是项目相关内容的详细介绍。

## 内容介绍

本项目主要针对宿舍维修服务进行设计与实现，包含以下功能模块：

1. 用户模块：负责用户注册、登录、个人信息管理等。
2. 维修申请模块：用户可在线提交维修申请，实时查看申请进度。
3. 维修人员模块：维修人员可接收维修任务，更新维修状态，提高工作效率。
4. 管理员模块：负责维修人员管理、维修项目管理、公告发布等。

通过本项目，我们希望解决宿舍维修过程中存在的沟通不畅、效率低下等问题，为广大师生提供更优质的维修服务。

## 技术介绍

本项目采用以下技术栈：

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于维修申请查询的核心代码：

```java
// 维修申请Service层
@Service
public class RepairApplyService {

    @Autowired
    private RepairApplyMapper repairApplyMapper;

    public List<RepairApply> getRepairAppliesByUserId(Integer userId) {
        RepairApplyExample example = new RepairApplyExample();
        example.createCriteria().andUserIdEqualTo(userId);
        return repairApplyMapper.selectByExample(example);
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

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/340782/2/5820/111813/68b73847Fdc5f4089/7e44e8de0d672795.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332541/6/8351/38612/68b7381fFf3f56a6d/42707d1ab49fdb68.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/334706/40/8187/33642/68b7381fF4d3ecff5/97833931e5bedee3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334394/17/8310/39373/68b7381fF890a667a/307a8e591b37dfac.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331447/14/8258/62519/68b73820Fe686d896/3a86df0f023e251e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337091/16/5765/211212/68b73821F2d51a37c/55c01601d9c4526e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339415/25/5787/61191/68b73821F730e41b9/aef8bc5c940d1991.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/333826/30/7898/66226/68b73821F91964216/c49659f8d238dd5d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/335995/39/5793/68378/68b73822F38962c28/4e7bb24ec1226ed1.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334345/9/8200/67038/68b73822Fe0fb15d1/04b81f472c14c818.jpg)

