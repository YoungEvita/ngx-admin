# 环境要求
1. 要安装 ngx-admin，您必须使用 NodeJS 版本 14.14+，这是因为应用程序中使用了 node-sass 的版本。
2. 14.20.1 本环境运行是所使用的node版本，如果需要安装其他版本，请使用 nvm 进行安装

# 安装运行
1. npm install
2. npm run start

# 开发环境修改
1. 开发环境默认端口为4200， 如果需要修改为其他端口，则修改`angular.json`文件中的"serve"配置项中的"port"值即可
2. 本环境修改为了4300端口
```json
"serve": {
    "builder": "@angular-devkit/build-angular:dev-server",
    "options": {
      "browserTarget": "ngx-admin:build",
      "port": 4300
    },
    "configurations": {
      "production": {
        "browserTarget": "ngx-admin:build:production"
      }
    } 
}



