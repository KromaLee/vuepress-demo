# 前端打包部署

## 1. 打包

> 已有现成的在线打包工具,不再推荐使用本地打包

1. 提交代码
2. 登陆[Jenkins](http://192.168.1.98:8088/)
3. 找到前端对应的任务,立即构建,即可完成开发服务器的前端打包和部署
4. 已建立定时任务,每晚自动打包部署一次

## 2. 部署

> 将打好的 jar 包放到开发服务器,并且脚本启动 jar 包,已在 Jenkins 任务中完成,无需额外手动操作
