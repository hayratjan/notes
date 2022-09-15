# vue3+vite

### 1、nvm node本地版本控制程序

    nvm list                   查看本地安装的node版本
    nvm list  available        查看可以安装的线上node版本
    nvm install 18..0         安装node18.8.0版本
    nvm use 18.8.0             切换到本地node18.8.0版本
    nod -v                     查看node环境
    
    
    
    命令    说明
    nvm list    查看已经安装的版本
    nvm list installed    查看已经安装的版本
    nvm list available    查看网络可以安装的版本
    nvm arch    查看当前系统的位数和当前nodejs的位数
    nvm install [arch]    安装制定版本的node 并且可以指定平台 version 版本号 arch 平台
    nvm on    打开nodejs版本控制
    nvm off    关闭nodejs版本控制
    nvm proxy [url]    查看和设置代理
    nvm node_mirror [url]    设置或者查看setting.txt中的node_mirror，如果不设置的默认是 https://nodejs.org/dist/
    nvm npm_mirror [url]    设置或者查看setting.txt中的npm_mirror,如果不设置的话默认的是：https://github.com/npm/npm/archive/.
    nvm uninstall    卸载指定的版本
    nvm use [version] [arch]    切换指定的node版本和位数
    nvm root [path]    设置和查看root路径
    nvm version    查看当前的版本
    
    

#### nrm 介绍

npm源建管理器，允许快速切换npm

    npm install -g nrm    安装nrm
    nrm ls                查看nrm所有的源
    nrm use taobao        切换到淘宝镜像
    nrm add wode www.baidu.com              nrm添加
    nrm test npm           查看延迟

### npm介绍

    npm run dev        运行npm项目

### vscode插件

volar （包括两个插件） 代码提示 （vue language features <volar> 和type script vue pulgin） 使用vue 3

vetur 使用vue2版本，使用vue3的时候要禁用这个