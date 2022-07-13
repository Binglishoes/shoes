


[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/Binglishoes/shoes) 

2.点击上面紫色`Deploy to Heroku`，会跳转到heroku app创建页面，应用程序名无需填写也能创建，名字会由heroku随机生成，选择节点（美国或者欧洲），新用户只需要自定义UUID码和CADDYIndexPage（参考：[Caddy主页配置](https://github.com/Binglishoes/shoes/blob/master/README.md))，其他建议保持默认，点击下面deploy，几秒后搞定！   

3.若出现`no.`提示，则返回仓库，>`Setting`>`Repository name`修改仓库名。

4.若执行了第3步修改仓库名的操作，则必须修改app.json中的name和description，

5.注意`repository`必须留空以免项目被禁

6.再修改`Deploy to Heroku`按键指向地址为自己仓库地址，重复`2`的操作


