### Repository  
仓库（即项目），如果你想在 Github 上开源一个项目，那就必须要新建一个 Repository 。  

### Issue  
别人发现你的项目中有bug，或者哪些地方做的不够好，他就可以给你提个 Issue ，然后你看到了这些问题就可以去逐个修复。  

### Star  
给项目点赞，但是在 Github 上的点赞远比微博、知乎点赞难的多。  

### Fork  
你开源了一个项目，别人想在你这个项目的基础上做些改进，然后应用到自己的项目中，这个时候他就可以 Fork 你的项目，他的 Github 主页上就多了一个项目，只不过这个项目是基于你的项目基础，他就可以随心所欲的去改进，但是丝毫不会影响原有项目的代码与结构。  

### Watch  
如果你 Watch 了某个项目，那么以后只要这个项目有任何更新，你都会第一时间收到关于这个项目的通知提醒。  

### Gist  
有些时候你没有项目可以开源，只是单纯的想分享一些代码片段，这个时候 Gist 就派上用场了！  

### Pull Request  
发起请求，这个其实是基于 Fork 的，如果别人在你基础上做了改进，后来觉得改进的很不错，应该要把这些改进让更多的人收益，于是就想把自己的改进合并到原有项目里，这个时候他就可以发起一个 Pull Request（简称PR） ，原有项目创建人就可以收到这个请求，这个时候他会仔细review你的代码，并且测试觉得OK了，就会接受你的PR，这个时候你做的改进原有项目就会拥有了。  

## Git Command  
1. git init  : 命令创建一个空的Git仓库或重新初始化一个现有仓库。  
2. git status : 用于显示工作目录和暂存区的状态。提交前查看下。  
3. git add : 命令将文件内容添加到索引(将修改添加到暂存区)。  
4. git commit : 命令用于将更改记录(提交)到存储库。  
5. git log : 命令用于显示提交日志信息。  
6. git show : 命令就可以查看修改的具体信息。(配合git log使用)  
7. git branch : 命令用于列出，创建或删除分支。  
8. git checkout : 命令用于切换分支或恢复工作树文件。  
9. git merge : 命令用于合并分支。  
10. git tag : 命令用于创建，列出，删除或验证使用GPG签名的标签对象。  
11. git rm : 命令用于从工作区和索引中删除文件。  
12. git clone : 命令将存储库克隆到新目录中。  
13. git pull : 命令用于取回远程主机某个分支的更新，再与本地的指定分支合并。  
14. git push : 命令用于将本地分支的更新，推送到远程主机。  
15. git remote : 命令用于操作远程库，创建、删除、查询等。  
16. git diff : 此命令比较的是工作目录中当前文件和暂存区域快照之间的差异,也就是修改之后还没有暂存起来的变化内容。  
17. git fetch : 从一个或多个其他存储库中获取分支和/或标签(统称为“引用”)以及完成其历史所必需的对象。  
18. git config : 命令用于获取并设置存储库或全局选项。  
