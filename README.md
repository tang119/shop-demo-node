## shop-demo-node

使用 Express + MongoDB 的小电商实战项目

## 开发环境

- Node.js: `6.11.0`
- MongoDB: `3.4.2`
- Express: `3.4.8`

## 目录

- 开发环境搭建
    - [Node.js 的安装与使用](https://github.com/18820227745/shop-demo-node/blob/master/book/1.1%20Node.js%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md)
        - [安装 Node.js](https://github.com/18820227745/shop-demo-node/blob/master/book/1.1%20Node.js%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md#111-安装-nodejs)
        - [n 和 nvm](https://github.com/18820227745/shop-demo-node/blob/master/book/1.1%20Node.js%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md#112-n-和-nvm)
        - [nrm](https://github.com/18820227745/shop-demo-node/blob/master/book/1.1%20Node.js%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md#113-nrm)
    - [MongoDB 的安装与使用](https://github.com/18820227745/shop-demo-node/blob/master/book/1.2%20MongoDB%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md)
        - [安装与启动 MongoDB](https://github.com/18820227745/shop-demo-node/blob/master/book/1.2%20MongoDB%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md#121-安装与启动-mongodb)
        - [Robomongo 和 MongoChef](https://github.com/18820227745/shop-demo-node/blob/master/book/1.2%20MongoDB%20%E7%9A%84%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8.md#122-robomongo-和-mongochef)
- Node.js 知识点讲解
    - [require](https://github.com/18820227745/shop-demo-node/blob/master/book/2.1%20require.md)
    - [exports 和 module.exports](https://github.com/18820227745/shop-demo-node/blob/master/book/2.2%20exports%20%E5%92%8C%20module.exports.md)
    - [Promise](https://github.com/18820227745/shop-demo-node/blob/master/book/2.3%20Promise.md)
    - [环境变量](https://github.com/18820227745/shop-demo-node/blob/master/book/2.4%20%E7%8E%AF%E5%A2%83%E5%8F%98%E9%87%8F.md)
    - [packge.json](https://github.com/18820227745/shop-demo-node/blob/master/book/2.5%20package.json.md)
        - [semver](https://github.com/18820227745/shop-demo-node/blob/master/book/2.5%20package.json.md#251-semver)
    - [npm 使用注意事项](https://github.com/18820227745/shop-demo-node/blob/master/book/2.6%20npm%20%E4%BD%BF%E7%94%A8%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md)
        - [npm init](https://github.com/18820227745/shop-demo-node/blob/master/book/2.6%20npm%20%E4%BD%BF%E7%94%A8%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md#261-npm-init)
        - [npm install](https://github.com/18820227745/shop-demo-node/blob/master/book/2.6%20npm%20%E4%BD%BF%E7%94%A8%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md#262-npm-install)
        - [npm scripts](https://github.com/18820227745/shop-demo-node/blob/master/book/2.6%20npm%20%E4%BD%BF%E7%94%A8%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md#263-npm-scripts)
        - [npm shrinkwrap ](https://github.com/18820227745/shop-demo-node/blob/master/book/2.6%20npm%20%E4%BD%BF%E7%94%A8%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md#264-npm-shrinkwrap)
- Hello, Express
    - [初始化一个 Express 项目](https://github.com/18820227745/shop-demo-node/blob/master/book/3.1%20%E5%88%9D%E5%A7%8B%E5%8C%96%E4%B8%80%E4%B8%AA%20Express%20%E9%A1%B9%E7%9B%AE.md)
        - [supervisor](https://github.com/18820227745/shop-demo-node/blob/master/book/3.1%20%E5%88%9D%E5%A7%8B%E5%8C%96%E4%B8%80%E4%B8%AA%20Express%20%E9%A1%B9%E7%9B%AE.md#311-supervisor)
    - [路由](https://github.com/18820227745/shop-demo-node/blob/master/book/3.3%20%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E.md)
        - [express.Router](https://github.com/18820227745/shop-demo-node/blob/master/book/3.2%20%E8%B7%AF%E7%94%B1.md#321-expressrouter)
    - [模板引擎](https://github.com/18820227745/shop-demo-node/blob/master/book/3.3%20%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E.md)
        - [ejs](https://github.com/18820227745/shop-demo-node/blob/master/book/3.3%20%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E.md#331-ejs)
        - [includes](https://github.com/18820227745/shop-demo-node/blob/master/book/3.3%20%E6%A8%A1%E6%9D%BF%E5%BC%95%E6%93%8E.md#332-includes)
    - [Express 浅析](https://github.com/18820227745/shop-demo-node/blob/master/book/3.4%20Express%20%E6%B5%85%E6%9E%90.md)
        - [中间件与 next](https://github.com/18820227745/shop-demo-node/blob/master/book/3.4%20Express%20%E6%B5%85%E6%9E%90.md#341-中间件与-next)
        - [错误处理](https://github.com/18820227745/shop-demo-node/blob/master/book/3.4%20Express%20%E6%B5%85%E6%9E%90.md#342-错误处理)
- 小电商项目实战
    - [开发环境](https://github.com/18820227745/shop-demo-node/blob/master/book/4.1%20%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83.md)
    - [准备工作](https://github.com/18820227745/shop-demo-node/blob/master/book/4.2%20%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C.md)
        - [目录结构](https://github.com/18820227745/shop-demo-node/blob/master/book/4.2%20%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C.md#421-目录结构)
        - [安装依赖模块](https://github.com/18820227745/shop-demo-node/blob/master/book/4.2%20%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C.md#422-安装依赖模块)
    - [配置文件](https://github.com/18820227745/shop-demo-node/blob/master/book/4.3%20%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6.md)
        - [config-lite](https://github.com/18820227745/shop-demo-node/blob/master/book/4.3%20%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6.md#431-config-lite)
    - [功能设计](https://github.com/18820227745/shop-demo-node/blob/master/book/4.4%20%E5%8A%9F%E8%83%BD%E8%AE%BE%E8%AE%A1.md)
        - [功能与路由设计](https://github.com/18820227745/shop-demo-node/blob/master/book/4.4%20%E5%8A%9F%E8%83%BD%E8%AE%BE%E8%AE%A1.md#441-功能与路由设计)
        - [会话](https://github.com/18820227745/shop-demo-node/blob/master/book/4.4%20%E5%8A%9F%E8%83%BD%E8%AE%BE%E8%AE%A1.md#442-会话)
        - [页面通知](https://github.com/18820227745/shop-demo-node/blob/master/book/4.4%20%E5%8A%9F%E8%83%BD%E8%AE%BE%E8%AE%A1.md#443-页面通知)
        - [权限控制](https://github.com/18820227745/shop-demo-node/blob/master/book/4.4%20%E5%8A%9F%E8%83%BD%E8%AE%BE%E8%AE%A1.md#444-权限控制)
    - [页面设计](https://github.com/18820227745/shop-demo-node/blob/master/book/4.5%20%E9%A1%B5%E9%9D%A2%E8%AE%BE%E8%AE%A1.md)
    - [连接数据库](https://github.com/18820227745/shop-demo-node/blob/master/book/4.6%20%E8%BF%9E%E6%8E%A5%E6%95%B0%E6%8D%AE%E5%BA%93.md)
        - [为什么使用 Mongoose](https://github.com/18820227745/shop-demo-node/blob/master/book/4.6%20%E8%BF%9E%E6%8E%A5%E6%95%B0%E6%8D%AE%E5%BA%93.md#461-为什么使用-mongoose)
    - [注册](https://github.com/18820227745/shop-demo-node/blob/master/book/4.7%20%E6%B3%A8%E5%86%8C.md)
        - [用户模型设计](https://github.com/18820227745/shop-demo-node/blob/master/book/4.7%20%E6%B3%A8%E5%86%8C.md#471-用户模型设计)
        - [注册页](https://github.com/18820227745/shop-demo-node/blob/master/book/4.7%20%E6%B3%A8%E5%86%8C.md#472-注册页)
    - [登出与登录](https://github.com/18820227745/shop-demo-node/blob/master/book/4.8%20%E7%99%BB%E5%87%BA%E4%B8%8E%E7%99%BB%E5%BD%95.md)
        - [登出](https://github.com/18820227745/shop-demo-node/blob/master/book/4.8%20%E7%99%BB%E5%87%BA%E4%B8%8E%E7%99%BB%E5%BD%95.md#481-登出)
        - [登录页](https://github.com/18820227745/shop-demo-node/blob/master/book/4.8%20%E7%99%BB%E5%87%BA%E4%B8%8E%E7%99%BB%E5%BD%95.md#481-登出)
        - [登录](https://github.com/18820227745/shop-demo-node/blob/master/book/4.8%20%E7%99%BB%E5%87%BA%E4%B8%8E%E7%99%BB%E5%BD%95.md#481-登出)
    - [添加商品](https://github.com/18820227745/shop-demo-node/blob/master/book/4.9%20%E6%B7%BB%E5%8A%A0%E5%95%86%E5%93%81.md)
        - [商品模型设计](https://github.com/18820227745/shop-demo-node/blob/master/book/4.9%20%E6%B7%BB%E5%8A%A0%E5%95%86%E5%93%81.md)
        - [浏览商品](https://github.com/18820227745/shop-demo-node/blob/master/book/4.9%20%E6%B7%BB%E5%8A%A0%E5%95%86%E5%93%81.md#492-浏览商品)
        - [添加商品](https://github.com/18820227745/shop-demo-node/blob/master/book/4.9%20%E6%B7%BB%E5%8A%A0%E5%95%86%E5%93%81.md#493-添加商品)
    - [购物车](https://github.com/18820227745/shop-demo-node/blob/master/book/4.10%20%E8%B4%AD%E7%89%A9%E8%BD%A6.md)
        - [购物车模型设计](https://github.com/18820227745/shop-demo-node/blob/master/book/4.10%20%E8%B4%AD%E7%89%A9%E8%BD%A6.md#4101-购物车模型设计)
        - [显示购物车商品](https://github.com/18820227745/shop-demo-node/blob/master/book/4.10%20%E8%B4%AD%E7%89%A9%E8%BD%A6.md#4102-显示购物车商品)
        - [添加购物车商品](https://github.com/18820227745/shop-demo-node/blob/master/book/4.10%20%E8%B4%AD%E7%89%A9%E8%BD%A6.md#4103-添加购物车商品)
        - [删除购物车商品](https://github.com/18820227745/shop-demo-node/blob/master/book/4.10%20%E8%B4%AD%E7%89%A9%E8%BD%A6.md#4104-删除购物车商品)
        - [结算](https://github.com/18820227745/shop-demo-node/blob/master/book/4.10%20%E8%B4%AD%E7%89%A9%E8%BD%A6.md#4105-结算)
    - [日志](https://github.com/18820227745/shop-demo-node/blob/master/book/4.11%20%E6%97%A5%E5%BF%97.md)
        - [winston 和 express-winston](https://github.com/18820227745/shop-demo-node/blob/master/book/4.11%20%E6%97%A5%E5%BF%97.md#4111-winston-和-express-winston)
        - [.gitignore](https://github.com/18820227745/shop-demo-node/blob/master/book/4.11%20%E6%97%A5%E5%BF%97.md#4112-gitignore)
    - [测试](https://github.com/18820227745/shop-demo-node/blob/master/book/4.12%20%E6%B5%8B%E8%AF%95.md)
        - [mocha 和 supertest](https://github.com/18820227745/shop-demo-node/blob/master/book/4.12%20%E6%B5%8B%E8%AF%95.md#4121-mocha-和-supertest)
        - [测试覆盖率](https://github.com/18820227745/shop-demo-node/blob/master/book/4.12%20%E6%B5%8B%E8%AF%95.md#4122-测试覆盖率)
    - [部署](https://github.com/18820227745/shop-demo-node/blob/master/book/4.13%20%E9%83%A8%E7%BD%B2.md)
        - [申请 MLab](https://github.com/18820227745/shop-demo-node/blob/master/book/4.13%20%E9%83%A8%E7%BD%B2.md#4131-申请-mlab)
        - [pm2](https://github.com/18820227745/shop-demo-node/blob/master/book/4.13%20%E9%83%A8%E7%BD%B2.md#4132-pm2)
        - [部署到 Heroku](https://github.com/18820227745/shop-demo-node/blob/master/book/4.13%20%E9%83%A8%E7%BD%B2.md#4132-部署到-heroku)
        - [部署到 UCloud](https://github.com/18820227745/shop-demo-node/blob/master/book/4.13%20%E9%83%A8%E7%BD%B2.md#4133-部署到-ucloud)


文档格式，知识点参考：[N-blog](https://github.com/nswbmw/N-blog/tree/master/book)

代码参考：[汇智网](http://www.hubwiz.com/course/?type=Node.js)
