## 踩坑合集



# fatal: refusing to merge unrelated histories

> 一般在重建git init后，关联远程仓库，git pull时出错

远程仓库已经存在代码记录了，并且那部分代码没有和本地仓库进行关联

**解决**

允许pull未关联的远程仓库旧代码

`git pull origin master --allow-unrelated-histories`

