# vue+vant+node+koa2+mongoose

> A Vue.js project

## Build Setup

``` bash
#前台
## install dependencies
npm install

## serve with hot reload at localhost:8080
npm run dev

## build for production with minification
npm run build

#后台（service目录）
## install dependencies
npm install

## serve with hot reload at localhost:3000
node index.js

```


## 首页（ShoppingMall）
###轮播图+商品推荐（vue-awesome-swiper）+商品楼层（组件封装floorComponent） +热卖商品（Lazyload）

## 列表页（CategoryList）
###一级分类（axios）+二级分类（van-tab）+商品列表（上拉和下拉van-pull-refresh）

## 购物车（Cart）
###商品信息（信息获取localStorage，金额计算totalMoney）

## 会员中心（Member）
###登录和注册（login信息与数据进行比对登录，register信息存储）

## 后台
### 将data_json导入mogodb koa2处理用户请求