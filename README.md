# git-practice

总结一下 git 的指令： 这些内容大多源于廖雪峰的内容以及掘金小册

> git log
> commit 右边的一大串字符：是 commit 的 SHA-1 校验(可以理解为 commit 的 ID)

> git status 是用来查看工作目录当前状态的指令 --> 提交代码之前先看看文件状态是个好习惯
> 你当前所在的分支 例如： `on branch main` --> 在`main`分支上。origin/main 中 main 是当前的分支， origin 是远程仓库的名称(默认名称)
> 红色是未被追踪(未 git add)，处于 not staged 状态(更改的代码未放入暂存区)
> 绿色是被追踪但未被提交(未 git commit) 但已处于 staged 状态（代码在暂存区->在.git 目录下的一个叫做 index 的文件里）

> git add + 文件名
> add 指定来让 Git 开始追踪代码。 会把更改的代码放进暂存区

> git commit + 文件名
> 将放在暂存区中被指定的文件进行提交。 这样的输入会进入一个界面，用来填写提交信息(commit message), 也可以简单写 git commit -m + "xxx"，这样把暂存区全部的内容都会提交到本地仓库

> git push
> 把本地的提交发布(即上传到中央仓库)，这是联网操作，会填写正确的账户和密码
