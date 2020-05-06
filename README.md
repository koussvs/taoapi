

## 使用技术

+ nodejs
+ nuxt.js
+ vant 

## 安装步骤

### 下载源码

``` bash
git clone https://github.com/luzhanbo/taobaokeapi.git
```

### 修改配置
1. nuxt.config.js 最后的环境参数，前端的访问地址
``` json
{
    "env":{
        "root":"[需要修改]前端的访问地址，如http://localhost:3000/"
    }
}
```

修改 server/config.js 的配置

### 运行命令

``` bash
# 安装依赖模块
使用yarn 安装
$ yarn install

使用npm 安装 
$ npm install

# 启动项目，可通过这个地址访问， http://localhost:3000/
使用yarn 运行
$ yarn dev

使用npm 运行
$ npm dev  

# 部署线上环境，先用以下命令构建，然后使用pm2 start进行部署 
使用yarn 构建 
$ yarn build

使用npm 构建
$ npm build 

$ pm2 start 

```


## 联系我 
+ QQ：1558825891
+ 留言：淘宝客API 
