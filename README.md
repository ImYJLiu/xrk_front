# 启动项目
``` bash
( 使用 nodeJs V17 以下的版本！！ )

# 查看node版本
node -v

# 卸载node(如果原版本高于V17，需要先卸载)
nvm uninstall <current_version>

# 安装node
1. 列出可安装的Node.js版本：
nvm ls-remote

2. 安装指定版本的Node.js，例如安装Node.js v14.18.1：
nvm install 14.18.1

3. 验证安装并切换到已安装的版本：
nvm use 14.18.1

4. 检查当前使用的Node.js版本：
node -v


# 切换镜像
npm config set registry https://registry.npmmirror.com

# 安装依赖
npm install --legacy-peer-deps

# 清除缓存
npm cache clean --force



# 启动项目
npm run dev

# 默认用户名和密码
admin 123456




# 项目概述

项目是基于SpringBoot+Vue前后端分离的仓库管理系统

后端：SpringBoot + MybatisPlus

前端：Node.js + Vue + element-ui 

数据库：mysql


