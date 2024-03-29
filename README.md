# shop
SSM+Vue开发网络商城
【Spring+SpringMVC+MyBatis+Bootstrap+Vue】
目录

【Spring+SpringMVC+MyBatis+Bootstrap+Vue】

1.系统功能介绍

1. 1 系统前台功能分析

1.2 系统后台功能分析

 项目功能效果图

后台管理模块：

 移动APP端：

1.系统功能介绍
      网上商城系统 - 的英文一个功能完善的用英语购物系统 - ，主要为在线销售和在线购物服务。其功能主要包含商品的管理，会员的管理，订单的管理，库存的管理，价格的管理，在线支付等。主要功能分为前台功能模块和后台功能模块。       

1. 1 系统前台功能分析
       前台面对用户，用户可在系统前台中浏览选择商品，并再登陆后可对所选择的商品加入购物车或者直接提交订单进行购买等。
       ![image](https://github.com/gqzGitHub/shop/blob/master/images/2018060715523638.png)


        ①在线浏览

        用户可在系统前台首页进行商品浏览，在多种多样的商品中选择自己中意的商品。

        ②用户注册

        对于未注册的用户，系统可以提供免费注册的功能。注册完成后，用户可进入系统的登陆界面，进行登陆操作。

        ③用户登陆

        对于商品购买以及商品加入购物车等功能，用户必须进行登陆后方可进行后续操作。用户可点击系统的登陆按钮，点击进入系统相应的登陆界面，完成用户的登陆操作。

        ④商品搜索

        琳琅满目的商品，让人眼花缭乱。找不到中意的商品，怎么办。商品搜索功能为你解决这个头痛的问题。用户可在商品搜索栏输入关键字，点击搜索，系统即可为其呈现想要的商品。

        ⑤商品详情查看

        在商品列表中找到了自己所想要的宝贝之后，用户可点击商品图标，进入详情页，查看商品更详尽的各项信息。

        ⑥商品加入购物车

        对于中意的宝贝，系统提供了购物车功能。即用户可以将自己比较纠结或者暂时不想购买的商品加入购物车，日后在做定夺，方便下次购买。

        ⑦订单支付

        系统为用户提供了支付功能，用户再找到自己所钟意的商品之后，可以选择支付，购买商品，完成本次操作。



1.2 系统后台功能分析
        管理员在后台，则可以对系统进行各项管理操作，包括滞销商品的下架，新增热门商品，以及对商品的价格，对商品的规格的选择，和库存量的管理等。

       ![image](https://github.com/gqzGitHub/shop/blob/master/images/2018060715542133.png)


        ①管理员登陆

        系统为后台管理员提供了登陆功能，管理员输入正确的用户名和密码，通过验证之后，可进入系统后台管理界面，查看商品信息，并对商品进行各项操作。

        ②后台商品列表展示

        后台商品种类繁多，不易查看。系统为管理员提供了相应的商品列表展示功能，将各种商品以表格形式，分页展示在商品列表界面，方便查看。

        ③后台商品查询

同样的，由于商品的种类繁多，不易一一查看。系统为后台用户提供了商品搜索功能，管理员可在搜索框，输入关键字，即可查得所要查看的商品内容。

        ④修改商品信息

商品的各项信息并不是一成不变的，由于库存或者活动等的原因，经常需要对商品信息进行修改。例如节日的商品打折，热销商品的库存添加等。

        ⑤删除商品

网络商城以盈利为主，对于滞销或者无人问津的冷门商品，要及时把它从商城列表中下架，删除这类商品，为新增的商品提供首页展示栏位。

        ⑥添加商品

商城商品的种类并不是一成不变的。为了商城的更好发展，往往需要及时添加当下热销的商品，以保持商城的更多盈利。系统在后台，为管理员提供了商品添加功能，为商城提供实时的，最热门的商品。

        ⑦商品库存管理

        对于同一件商品，它具有不同的规格属性。比如尺码，颜色等不同属性。在后台需要对不同的规格库存进行定期盘算，以便满足供求关系。

    数据库设计

项目架构
      
 项目功能效果图
 ![image](https://github.com/gqzGitHub/shop/blob/master/images/20180607160050241.png)
 ![image](https://github.com/gqzGitHub/shop/blob/master/images/20180607160235560.png)
 ![image](https://github.com/gqzGitHub/shop/blob/master/images/20180712143209402.png)

后台管理模块：
 ![image](https://github.com/gqzGitHub/shop/blob/master/images/20190506233633974.png)

[ 点击下载] 项目完成代码             打赏

 移动APP端：

  【商城移动APP 】开发文档     Reward

本项目提供部分简单的API，更多详细的API请联系作者：

获取商品分类  

http://ganquanzhong.top/shop/getCategories

获取轮播商品图片

http://ganquanzhong.top/shop/getProductPic

获取最新商品

http://ganquanzhong.top/shop/getNewProduct

获取热门商品

http://ganquanzhong.top/shop/getHotProduct 

```xml 

项目配置说明书：

1.使用MySQL图形化工具新建数据库shop，右键运行shop.sql文件。完成数据库建立。

2.使用MyEclipse或Eclipse导入项目shop，右键build path配置jar包。保证项目是web工程，并且添加需要的依赖。

3.修改数据库配置信息，保存数据库连接是自己的username、password

4.将项目部署到tomcat8.0服务器上，在浏览器里面访问项目。【此时项目中的图片不能加载。还需要配置虚拟路径，看下面说明】

        需要把ShopFile文件夹复制到E盘根路径配置虚拟路径哈【E:\\ShopFile\\upload\\】

       在tomcat中配置虚拟路径，视频文件存放的位置！
       <Context docBase="E:\\ShopFile\\upload\\" path="/upload" reloadable="true"/>
```
