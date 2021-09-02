# Git指令相关信息：

merge：

- git merge 到主分支（master/main）时可以改**黄色**注释、也可以直接无视按VIM的 ：wq 强制退出保存即可
- git merge 默认为Fast-Forward
  - 合并后无需Commit



checkout

- git checkout -b *branchName* 拷贝**当前branch**内容为基本内容



branch

- git branch -a

- git branch -d *branchName*  删除本地分支
- git push origin --delete *branchName* 删除远端



push：

- git push --set-upstream (origin *branchName*)



版本回退：

- git reset HEAD^
- git reset HEAD~*num*
- git reset HEAD *logid*

