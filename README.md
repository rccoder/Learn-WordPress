《WordPress的进阶之路》
===
这是一本聚集众多人的心血产生的书，所有内容面向互联网免费开放。

发起原因
===
WordPress无论在国外还是国内一直是一个比较火的博客软件，或者说是一个CMS软件。有关WordPress的教程在网上是多之又多，于此同时也避免不了鱼龙混杂的状况，很多教程只是死板的粘贴复制，没有讲透彻他的道理，导致WordPress的使用者越来越困惑。

偶然间看到GitBook能利用Markdown免费快速的制作精美的书籍，一时间便诞生了这个想法。

希望正如大家所希望的一样，这本书能在一年之内由大家一起完成他的出版，然后免费发布在互联网上。

时间
===
2015年7月5号开始，截至日期不定（这是一本活书，而不是一本死书）

协作方式
===
通过GitHub进行协作，文章格式采用Markdown。最后托管在gitbook平台，可转化为Epub/PDF/mobi等多种格式。

参与协作的朋友只需撰写更新Markdown文件内容，我会将内容转化成页面更新到gitbook平台与github的gh-pages分支。

如何参与
===
1. fork 这个项目
* 把fork过去的项目（也就是你的GitHub下面的那个项目）克隆到本地
* 运行 ```git branch develop``` 创建一个新的分支
* 运行 ```git checkout develop```切换到你刚才创建的 ```develop``` 分支
* 运行 ```git remote add upstream https://github.com/rccoder/Learn-WordPress```把我的仓库添加为远程仓库
* 运行 ```git remote update```进行更新
* 运行 ```git fetch upstream master```拉取我的库到本地
* 运行 ```git rebase upstream/master``` 拉取我的更新合并到你的分支

这只是一个初始化的流程，只需要做一遍就行，之后一直在develop分支进行修改即可。

如果我的库有了更新，请重复6-8步。

修改之后，登录你的GitHub, 然后进行```pull request```

**或者你可以查看这篇文章：[同步一个 fork](http://gaohaoyang.github.io/2015/04/12/Syncing-a-fork/)**

贡献内容
===
 * 错别字/措辞/图文修饰 - 直接发送pull request
 * 相关建议直接进行review或者在issues提交问题
 
作者
===
……