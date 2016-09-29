# workflow
## 第一步
### 1. fork repo右上角
### 2. 将自己fork的repo git clone到本地


## 同步更新fork的代码操作
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

