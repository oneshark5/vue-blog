# vue-blog
后端Java 前端Vue搭建的个人博客
## 开发流程
- Java练手demo
- 选定技术栈
- 开发接口
- 前端页面
- 添加功能
  - 登录评论
  - 文章点赞
  - 根据文章内容评论
- 根据功能添加微服务、TDMQ
  
## 视频记录
- easycode插件
  配置idea操作mysql，添加lombok生成模板。
- 前台页面需求

## git操作
- `git pull` 相当于git fetch + git merge 
- `git reset --hard HEAD`忽略本地修改，拉取新的
**将代码push到git**
1. `git add .`将所有的修改添加到暂存库
`git add [file1] [file2]`多个文件采用空格隔开。
`git add [dir]`也可以将指定目录添加到暂存区，包括子目录。
2. `git commit -m "注释内容"`
将暂存区内容添加到本地仓库中。
3. `git push origin main`
将本地的分支版本上传到远程并合并
git push <远程主机名> <本地分支名>
4. git回退
