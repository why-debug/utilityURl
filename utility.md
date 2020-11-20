
### 各种干货视频及各种软件安装包地址

* [后台系统的权限控制与管理【完结】](https://www.bilibili.com/video/BV15Q4y1K79c?from=search&seid=13581687011867552931)
* [git各版本下载地址【全版本】](https://npm.taobao.org/mirrors/git-for-windows/)

#### document.body.style.overflow = "hidden"; //禁止主页面滚动

### 解决因为本地代码和远程代码冲突，导致git pull无法拉取远程代码的问 
[地址](https://www.cnblogs.com/zhujiabin/p/9140863.html)

#### 一般解决办法：
* 1、git stash 将本地代码stash到仓库中。
可以使用git stash save ***定义自己的标记，方便以后查询
* 2、git pull 将远程代码拉取到本地。
* 3、git stash pop 将仓库中的代码合到本地最新代码中。
* 4、在处理bug的过程中，可能存在多次stash的操作。这时可以使用git stash list查看本地仓库中都存储了几个stash版本。
* 5、git stash pop默认将最近一次stash操作合并到本地代码中，也可以通过git stash pop stash@{Number}指定将某次    stash的内容合并到本地代码中。
* 6、git stash pop命令在合并代码的同时，会把仓库中对应的内容弹出。如果只想查看，而不想弹出内容，可以使用git stash apply命令进行操作。
* 7、git stash -h 查看git stash帮助
* 8、git stash show 显示stash合并到本地代码后，哪些文件会修改，以及修改的概述
* 9、git stash show -p stash@{0} 显示修改的详细内
### a标签下载文件：
```
handleOk() {
      let link = document.createElement("a");
      link.download = "附件1.xls";  //下载文件名
      link.href = "附件1.xls";  // 提供文件地址，或者后端接口地址
      document.body.appendChild(link);
      link.click();
},

```
