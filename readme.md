### 这个项目里面的一些内容都是平常开发用到的内容，包括面试被问到，就相应的记录下

#### 关于gitHub指令是写东西的时候。偶尔犯错找到的解决方式
##### 突然有一天发现自己傻傻的把node_modules包给传到girhub上了-_-!
##### 所以想要删除代码仓库上的这个文件夹，但是网页上只提供删除文件。。。。。
```
git rm -r --cached .idea  #--cached不会把本地的.idea删除
git commit -m 'delete .idea dir'
git push -u origin master

```