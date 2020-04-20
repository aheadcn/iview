基于iview 3.5.1 版本
分支：
wec-iview

# 切换镜像源，登录 NPM 私有仓库
nrm ls

nrm use sinopia

nrm login

# 编绎发布

npm run prepare

npm publish 

# 更新官方版本方法：

upstream 为官网源

git fetch upstream

git merge upstream/v3.5.1
