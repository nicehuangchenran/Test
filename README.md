### git指令记录
## git init 在此目录下创建一个git，生成.git文件

## git remote add origin git@github.com:RuiTan/test.git 添加远程仓库，origin是远程仓库的别名

## git remote -v 查看本地仓库所链接的远程仓库，
	$ git remote -v
	origin  git@github.com:nicehuangchenran/Test.git (fetch)
	origin  git@github.com:nicehuangchenran/Test.git (push)

## git pull origin main 从origin远程仓库拉取main branch到本地
## git branch 查看本地repo的branch
## git branch -d local_branch_name 删除本地branch
## git push remote_name -d remote_branch_name 删除远程repo的branch
## git checkout -b first-branch 增加一个branch
## git checkout branch-name 切换branch

## git add . 将分支中的内容上传到本地缓冲区（index）
## git status 查看当前本地repo分支状态
## git commit -m "增加了一个git总结文档" commit到本地repo

## git push -u origin first-branch 发起push，项目创建者可以据此创建pull request,创建pull request后可以选择merge到base branch

