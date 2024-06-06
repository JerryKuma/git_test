# git_test
A repository to try git

常用git命令：
git --version 查看版本
git clone (ssh) 克隆github项目至本地仓库
git status 查看所有未注释且未被git跟踪的文件 当某个文件被本地创建后 默认不会被git跟踪
git add xxx.xx \ git add . 将某个(所有)文件添加到git跟踪
git restore --staged xxx.xx 将某个文件取消git跟踪
git rm "xxx.xx" 删除文件
git restore "xxx.xx" 恢复删除文件
git mv "xxx1.xx" "xxx2.xx" 文件改名 1->2
git commit -m "xxx" 对本次修改进行提交保存并评论状态 此时修改内容存在于分支中
git commit -m "xxxx" --amend 修改上次提交的评论状态 而不再进行一次提交
git log （--oneline）查看提交记录（单行显示）
git log -p 查看详细提交记录
git push origin main 远程合并到github仓库master分支
