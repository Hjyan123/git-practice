# Git 版本管理实践报告

## 一、学习资料来源及链接
1. Git 官方文档：https://git-scm.com/doc
2. GitHub 官方使用指南：https://docs.github.com/zh
3. 哔哩哔哩GitHub使用教程

## 二、实践流程
1. 下载并安装 Git，完成用户名与邮箱配置
2. 创建本地文件夹 `D:\GitWork`，使用 `git init` 初始化本地仓库
3. 在 GitHub 创建公开仓库 `git-practice`，复制仓库地址
4. 关联本地仓库与远程仓库：`git remote add origin 仓库地址`
5. 添加文件并完成 3 次提交，最后推送到 GitHub 远程仓库

## 三、每次提交内容说明
1. 第一次提交：添加 `English.html` 初始文件到本地仓库
2. 第二次提交：修改并完善 `English.html` 的文本内容
3. 第三次提交：优化文件格式，补充细节并完成最终版本

## 四、遇到的问题及解决方法
1. 问题：`git push` 时无法连接 GitHub，提示 `Connection was reset`
   解决方法：配置网络代理，同时关闭 Git 的 SSL 证书校验，成功连接并推送代码。
2. 问题：提交时 `git add` 找不到文件，提示 `pathspec did not match any files`
   解决方法：改用 `git add .` 命令添加当前目录下所有文件，避免文件名识别问题。
3. 问题：身份验证失败，无法推送代码
   解决方法：通过浏览器完成 GitHub 账号授权，成功获取推送权限。

## 五、Git 学习心得
通过本次实践，我掌握了 Git 的基础命令、本地仓库管理、远程仓库关联与推送的完整流程，理解了版本控制的核心意义。这次实践也让我熟悉了 GitHub 的基本操作，为后续的项目开发与代码管理打下了扎实的基础。
