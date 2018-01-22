# ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统

[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)](https://travis-ci.org/Jimmey-Jiang/ABP-ASP.NET-Boilerplate-Project-CMS)
[![Github Releases (by Asset)](https://img.shields.io/github/downloads/atom/atom/latest/atom-amd64.deb.svg)](https://github.com/Jimmey-Jiang/ABP-ASP.NET-Boilerplate-Project-CMS)
[![NuGet](https://img.shields.io/nuget/v/DotnetSpider2.Extension.svg)](https://www.nuget.org/packages)
[![Plugin on redmine.org](https://img.shields.io/redmine/plugin/stars/redmine_xlsx_format_issue_exporter.svg)](https://github.com/Jimmey-Jiang/ABP-ASP.NET-Boilerplate-Project-CMS)
[![Eclipse Marketplace](https://img.shields.io/eclipse-marketplace/last-update/notepad4e.svg)](https://github.com/Jimmey-Jiang/ABP-ASP.NET-Boilerplate-Project-CMS)
[![JIRA sprint completion](https://img.shields.io/jira/sprint/https/jira.spring.io/94.svg)](https://github.com/Jimmey-Jiang/ABP-ASP.NET-Boilerplate-Project-CMS)
[![](https://img.shields.io/bitbucket/issues-raw/atlassian/python-bitbucket.svg)](https://github.com/Jimmey-Jiang/ABP-ASP.NET-Boilerplate-Project-CMS)

## 工具支持

     visual studio 2017

     sql server 2008以上

     Redis :下载的Redis https://github.com/MicrosoftArchive/redis/releases 
     
 ##  打开方式
 
 
  1.  clone项目，然后visual studio 2017打开。
  
  2.  包还原（如果是直接clone本项目，这一步可以省略）。
  
  
  3.  新建一个空的数据库，并修改项目中数据库连接，指向刚建好的空的数据库。
  
  
  4.  工具 -> nuget包管理器-> 程序包管理控制台 下面选中xxxxentityframework,然后输入Update-Database 会自动生成数据库。
  
  5.  运行项目 用户名:admin 密码123qwe 即可看到效果，不懂地方参考博客园文章。
  
   打开方式详细可以参考第一章：http://www.cnblogs.com/anyushengcms/p/abp.html
     
## 博客园地址 

如果不知道怎么用，请前往个人博客园看下教程，博客园地址：http://www.cnblogs.com/anyushengcms/p/7325126.html

          
  ##  简介

   这也是算是一种学习的方法和态度吧,经常去学习和总结,写下一点对于ABP(ABP是“ASP.NET Boilerplate Project (ASP.NET样板项目)”的简称)框架的理解和运用.

       "ASP.NET Boilerplate是一个用最佳实践和流行技术开发现代WEB应用程序的新起点，它旨在成为一个通用的WEB应用程序框架和项目模板。"

        "ASP.NET Boilerplate 基于DDD的经典分层架构思想，实现了众多DDD的概念（但没有实现所有DDD的概念）。"

## 效果图

 ![1.png](http://upload-images.jianshu.io/upload_images/6855212-8d191ff98c8946f2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


![2.png](http://upload-images.jianshu.io/upload_images/6855212-7a978b6886d1768c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![3.png](http://upload-images.jianshu.io/upload_images/6855212-db94be8a19ad98d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](http://upload-images.jianshu.io/upload_images/6855212-9bd286dec4b39722.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](http://upload-images.jianshu.io/upload_images/6855212-3e5b67fa4b0b3364.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](http://upload-images.jianshu.io/upload_images/6855212-309ab925f4e486af.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](http://upload-images.jianshu.io/upload_images/6855212-c418ca1f07e972a1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](http://upload-images.jianshu.io/upload_images/6855212-a4f5193ff1440099.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


 ## 初衷

   学而时习之,不亦说乎,温顾温知新,可以为师矣.

 这其实是一个 abp框架的入门项目，尽管网上有很多资料，但是我们要自己动手去敲一遍代码，于是就有了这一系列文章，看懂远不如动手去做,动手做才能发现很多自己不懂的问题,不断的反思和总结,“乐于分享是一种境界的突破”。" 分享是很有意思，也是可以锻炼人的。 分享意味着自我的不断净化提升，不给自己后退的余地。为什么这么说呢？因为：一，分享的就是你所知道的，你所知道的是你投资时间和精力学来的，分享意味着你做到无私地把它分享出更高的价值，这是很伟大的。二，分享意味着你要不断去追寻新知，这很重要。只有用心生活，用心体会，才能不断有新的东西分享。这就是善于借用外力来完善自己的表现。。三，我们在分享的过程中，学会进一步判断，进一步深入思考，从而进一步提升思绪。这很重要，自己要了解自己，这是一个不断学习的过程。"

### 下面是这期文章的目录：

**（1）[ABP+AdminLTE+Bootstrap Table权限管理系统第一节--使用ASP.NET Boilerplate模板创建解决方案](http://www.cnblogs.com/anyushengcms/p/abp.html)**

**（2）[ABP+AdminLTE+Bootstrap Table权限管理系统第二节--数据库脚本](http://www.cnblogs.com/anyushengcms/p/7448804.html)**

**（3）[ABP+AdminLTE+Bootstrap Table权限管理系统第三节--abp分层体系及实体相关](http://www.cnblogs.com/anyushengcms/p/7259053.html)**

**（4）[ABP+AdminLTE+Bootstrap Table权限管理系统第四节--仓储,服务,服务接口及依赖注入](http://www.cnblogs.com/anyushengcms/p/7261778.html)**

**（5）[ABP+AdminLTE+Bootstrap Table权限管理系统第五节--WBEAPI及SwaggerUI](http://www.cnblogs.com/anyushengcms/p/7261782.html)**

**（6）[ABP+AdminLTE+Bootstrap Table权限管理系统第六节--abp控制器扩展及json封装以及6种处理时间格式化的方法](http://www.cnblogs.com/anyushengcms/p/7261795.html)**

**（7）[ABP+AdminLTE+Bootstrap Table权限管理系统第七节--登录逻辑及abp封装的Javascript函数库](http://www.cnblogs.com/anyushengcms/p/7261809.html)**

**（8）[ABP+AdminLTE+Bootstrap Table权限管理系统第八节--ABP错误机制及AbpSession相关](http://www.cnblogs.com/anyushengcms/p/7261815.html)**

**（9）[ABP+AdminLTE+Bootstrap Table权限管理系统第九节--AdminLTE模板页搭建](http://www.cnblogs.com/anyushengcms/p/7261822.html)**

**（10）[ABP+AdminLTE+Bootstrap Table权限管理系统第十节--AdminLTE模板菜单处理](http://www.cnblogs.com/anyushengcms/p/7261827.html)**

**（11）[ABP+AdminLTE+Bootstrap Table权限管理系统第十一节--Bootstrap Table用户管理列表以及Module Zero之用户管理](http://www.cnblogs.com/anyushengcms/p/7261834.html)**

**（12）[ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统第十二节--小结,Bootstrap Table之角色管理以及module-zero角色管理](http://www.cnblogs.com/anyushengcms/p/7435852.html)**

**（13）[ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统第十三节--RBAC模式及ABP权限管理（附送福利）](http://www.cnblogs.com/anyushengcms/p/7880038.html)**

 **（14）[ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统第十四节--后台工作者HangFire与ABP框架Abp.Hangfire及扩展](http://www.cnblogs.com/anyushengcms/p/7927314.html)**

 **（15）[ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统第十五节--缓存小结与ABP框架项目中 Redis Cache的实现](http://www.cnblogs.com/anyushengcms/p/8013201.html)**

**（16）[ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统第十六节--SignalR与ABP框架Abp.Web.SignalR及扩展](http://www.cnblogs.com/anyushengcms/p/8035924.html)**

 **（17）[ABP module-zero +AdminLTE+Bootstrap Table+jQuery权限管理系统第十七节--Quartz与ABP框架Abp.Quartz及扩展](http://www.cnblogs.com/anyushengcms/p/8037569.html)**
 
 ## 番外篇--Moddule Zero 

 > 注：番外篇参考自（https://github.com/ABPFrameWorkGroup）
 
 [番外篇--Moddule Zero介绍](http://www.cnblogs.com/anyushengcms/p/8309115.html)

[番外篇--Moddule Zero安装](http://www.cnblogs.com/anyushengcms/p/8309136.html)

[番外篇--Moddule Zero启动模板](http://www.cnblogs.com/anyushengcms/p/8309144.html)

[番外篇--Moddule Zero多租户管理](http://www.cnblogs.com/anyushengcms/p/8309150.html)

[番外篇--Moddule Zero 版本管理与组织单位管理](http://www.cnblogs.com/anyushengcms/p/8309167.html)

未完待续...

### 运用到的服务端技术:

- [ABP（ASP.NET BolierPlate ProJect）](https://github.com/aspnetboilerplate)
- [Module-Zero](https://github.com/aspnetboilerplate/module-zero)
- [ASP.NET MVC](http://www.asp.net/mvc)
- [ASP.NET Web API](http://www.asp.net/web-api)
- [ASP.NET Identity Framework (and social login extensions)](http://www.asp.net/identity)
- [ASP.NET Web Optimization Framework](http://www.asp.net/mvc/overview/performance/bundling-and-minification)
- [ASP.NET Web Pages](https://docs.microsoft.com/zh-cn/aspnet/web-pages/)
- [SignalR](http://www.asp.net/signalr)
- [EntityFramework](http://www.asp.net/entity-framework)
- [EntityFramework.DynamicFilters](https://github.com/jcachat/EntityFramework.DynamicFilters)
- [Castle Windsor](http://www.castleproject.org/projects/windsor/)
- [AutoMapper](http://automapper.org/)
- [HangFire](http://hangfire.io/)
- [Log4Net](https://logging.apache.org/log4net/)
- [xUnit](https://xunit.github.io/)
- [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle)
- [StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis)
- [SharpZipLib](http://icsharpcode.github.io/SharpZipLib/)
- [System.Linq.Dynamic](https://github.com/kahanu/System.Linq.Dynamic)

### 客户端:(前端是用的AdminLTE,Bootstrap  table.是开源的,不涉及版权)
- [Twitter Bootstrap](http://getbootstrap.com/)
- [Bootstrap Hover Dropdown](https://github.com/CWSpear/bootstrap-hover-dropdown)
- [Bootstrap Date Range Picker](https://github.com/dangrossman/bootstrap-daterangepicker)
- [Bootstrap Switch](http://www.bootstrap-switch.org/)
- [Bootstrap Select](http://silviomoreto.github.io/bootstrap-select)
- [Bootstrap table](http://bootstrap-table.wenzhixin.net.cn/)
- [jQuery](http://jquery.com/)
- [jQuery UI](http://jqueryui.com/)
- [jQuery BlockUI](http://malsup.com/jquery/block/)
- [jQuery Validation](http://jqueryvalidation.org/)
- [jQuery Ajax Forms](http://malsup.com/jquery/form/)
- [Js Cookie](https://github.com/js-cookie/js-cookie)
- [Modernizr](http://modernizr.com/)
- [Moment.js](http://momentjs.com/)
- [Moment.js Timezone](http://momentjs.com/timezone/)
- [Underscore.js](http://underscorejs.org/)
- [JsTree](https://www.jstree.com/)
- [Respondjs](https://github.com/scottjehl/Respond)
- [Font-Awesome](http://fontawesome.io/)
- [SpinJs](http://fgnass.github.io/spin.js/)
- [SweetAlert](http://t4t5.github.io/sweetalert/)
- [Toastr](http://codeseven.github.io/toastr/)
- [AdminLTE](https://adminlte.io/themes/AdminLTE/index2.html)

最后喜欢的请点下star



