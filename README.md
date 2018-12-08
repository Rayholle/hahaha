# hahaha
try to push a .txt firstly
/**************************************2018.12.8**************************************/
/**************************************RuiZhi**************************************/
第一次使用github上传文件
接下来想要上传几个简单项目和刷题经验内容等
这里记录一下git上传的命令和步骤：
1、首先要建立github与本地仓库的链接，即github创建好新的repository后，将其url复制，在本地目录下git clone $url
这样将github上的文件clone到本地目录
2、本地目录下git init创建.git记录文件
3、本地目录下git add [需要上传的文件内容（全部文件用'.'）,将add的内容添加到仓库
4、本地目录下git commit -m "注释"（git add命令主要用于把我们要提交的文件的信息添加到索引库中，
   当我们使用git commit时，git将依据索引库中的内容来进行文件的提交）。
5、本地目录下git remote add origin $url(自己仓库的url)建立远程连接，将本地仓库关联到github上
6、最后一步push之前add的内容：git push -u origin master（origin指代当前url）

