

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
## 付费说明 
付费只有一个差异就是不会像免费的那样限制你的请求次数。
如果你有任何疑问或者未能实现的功能，请千万别带着接口付费的目的找我。
我平时忙，可能没时间回复你的问题。

企业大客户请加QQ私聊，并告知来由。目前对个人和中小工作室提供以下收费档次：

| 类型 | 月缴 | 季度 | 独立部署 |
| ----- | ----- | ----- | ----- |
| 费用 | 550/月 |500/月，共1500元 |10000/次|

*独立部署是我在同个区域部署一套接口，提供外网IP给你调用。实例规格和区域自选，另外付费。
*按季度缴费更加优惠。
*不会限制授权的淘宝账号，增加授权不会另外收费。
*付费用户做IP白名单限制，需要把你服务器IP都发给我。
*如果发现有公开给其他人使用的情况，将直接中止合作。

