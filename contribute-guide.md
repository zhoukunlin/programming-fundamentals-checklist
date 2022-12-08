# Contribute Guide

## 1.Fork Repository

将项目从"White Belt keep Crawling" Fork到你自己的Github账号中

1. 进入仓库“programming-fundamentals-checklist”后，点击“Fork”按钮：

![image-20221208191804399](.\images\image-20221208191804399.png)

2. 接下来，点击“Create fork”按钮，将仓库Fork到自己的账号中：

![image-20221208191837686](.\images\image-20221208191837686.png)

## 2.将仓库克隆到本地

推荐使用SSH访问Github，截图以HTTPS为例

1. 获取仓库地址：

![image-20221208191939476](.\images\image-20221208191939476.png)

2. 打开相应操作系统的命令行，Windows以PowerShell为例，在命令行中输入下面的命令将仓库克隆到本地：

   ```powershell
   cd d:\projects\ #这里，通过cd命令进入到你想要保存仓库的磁盘路径
   git clone https://github.com/vwumumu/programming-fundamentals-checklist.git  #这里，clone后面的内容，是您仓库的路径。
   ```

   ![image-20221208192025698](.\images\image-20221208192025698.png)

## 3.更新文档

​	帮助更新、补充base.md文件，或者创建带有您注释的checklist文件，以更新base.md文件为例：

1. 用markdown文件编辑工具，如Typora，VSCode打开克隆到本地的仓库中的base.md文件，并添加下面红框中内容：

   ![image-20221208195536093](.\images\image-20221208195536093.png)

2. 通过命令：`git status`检查文件的变化：

   ![image-20221208195714301](.\images\image-20221208195714301.png)

   可以看到，base.md文件做了变更，这里请忽略“Untracked files”的内容。

3. 通过命令：`git add base.md`将文件的变化提交给git：

   ![image-20221208195903504](.\images\image-20221208195903504.png)

4. 通过命令：`git commit -m 'add 2.1 to base.md'`为变更添加备注信息：

   ![image-20221208200034182](.\images\image-20221208200034182.png)

5. 通过命令：`git push`将本地变更推送至自己个人账号的Github仓库中：

   ![image-20221208200121607](.\images\image-20221208200121607.png)

## 4.更新至小白慢爬营仓库

1. 在个人的仓库页面，点击“Pull requests”标签，点击“New pull request”按钮，创建“Pull Request”:

   ![image-20221208200321258](.\images\image-20221208200321258.png)

2. 观察“Pull Request”的方向，默认就是从个人到小白慢爬营，确认无误，点击“Create pull request”：

   ![image-20221208200547902](.\images\image-20221208200547902.png)

3. 填写说明信息后点击“Create pull request”：

   ![image-20221208200747357](.\images\image-20221208200747357.png)

至此，完成了协作，小白慢爬营的管理员将审核提交的内容，并合并到小白慢爬营的仓库中。
