2021/5/25
初始化项目：
问题一：webpack-dev-server启动报错Error: Cannot find module ‘webpack-cli/bin/config-yargs‘
解决方案：
1.卸载webpack-cli

npm uninstall webpack-cli
复制代码
2.安装webpack-cli版本3

npm install webpack-cli webpack-cli@3.3 -S

npm run start 启动项目