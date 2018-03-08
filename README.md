# workflow
## 第一步
### 1. fork repo右上角
### 2. 将自己fork的repo git clone到本地


## 同步更新fork的代码流程
### 1. 在本地代码中添加源代码库
  git remote add workflow https://github.com/Zhangzhiyue/workflow.git
### 2. 保证本地目前是在master分支上
  git checkout master
### 3. fetch源代码库
  git fetch workflow
### 4. merge源代码库的master代码到 本地的master上
  git merge workflow/master
### 5. 更新fork的master代码库
  git push origin master

## 提交代码流程
### 1. 本地fork的代码库中新建需要做的功能分支如：
  git checkout -b hotfix/easy-bug
### 2. 修改完代码，add和commit后，将分支hotfix/easy-bug push到origin
  git push origin hotfix/easy-buggit
### 3. 在github网站使用PR
  new pull request -->在自己folk的那一栏选择branch hotfix/easy-bug。
  提交pull request
### 4. 有权限的人员对PR进行merge 或close操作
