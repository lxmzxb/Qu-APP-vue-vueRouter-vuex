run # xyy-vue

> 一个集运动、锻炼、出游、交友、社交为一体的非常新颖的针对大学生的平台。旨在让现在的大学生抛开过去枯燥乏味、单一的生活方式，去认识更多的朋友、扩展自己的人脉圈，属个人项目。

### 技术栈

#### 前台
> * vue
> * vue-router
> * vuex
> * axios
> * es6
> * localStorage
> * webpack

#### Api
> * 约行列表 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/travelList](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/travelList)
> * 约行详情 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/travelDetail/:id](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/travelDetail/:id)
> * 约跑列表 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/sportList](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/sportList)
> * 约跑详情 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/sportDetail/:id](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/sportDetail/:id)
> * 用户信息 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/userInfo](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/userInfo)
> * 我的约行 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/myTravel](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/myTravel)
> * 发布约行个数 [https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/getPubToTravelNum](https://www.easy-mock.com/mock/5c6b6b1815b74a0aacc7a902/xyy/api/getPubToTravelNum)
首页轮播图
首页热门活动
约跑步活动列表
约出行活动列表
个人中心
查看个人活动
学生认证(待开发)
学生信息修改
消息通知(后台接口待开发)
选择高校(待开发)
登录
注册
活动详情
活动报名
活动发布
时间选择组件
地址选择组件
文件上传

|——xyy-vue/
|   |——build/
|   |——confg/
|   |——node_modules/
|   |——src/
|   |   |——assets/                 //静态文件
|   |   |——components/             //公共组件
|   |   |——fetch/
|   |   |——pages/                  //存放项目页面
|   |   |   |——Detail.vue          //活动详情页面
|   |   |   |——Home.vue            //首页
|   |   |   |——Login.vue           //登录页面
|   |   |   |——Navbar.vue          //我的发布
|   |   |   |——NotFound.vue        //出错页面
|   |   |   |——Post.vue            //发布活动页面
|   |   |   |——Regist.vue          //注册页面
|   |   |   |——Set.vue             //设置页面
|   |   |   |——Sport.vue           //约跑步活动列表页面
|   |   |   |——Travel.vue          //约出行活动列表页面
|   |   |   |——User.vue            //个人中心页面
|   |   |   |——UserInfo.vue        //个人详情页面
|   |   |   |——UserMsg.vue         //消息列表页面
|   |   |——router/
|   |   |   |——index.js            //页面路由
|   |   |——util                    //公用方法
|   |   |——vuex /                  //存放vuex代码
|   |   |   |——modules /           //数据模块
|   |   |   |——store.js            //vuex主入口
|   |   |   |——types.js            //vuex的types文件
|   |   |——App.vue                 //父组件
|   |   |——main.js                 //入口文件
|   |——static/
|   |——.babelrc
|   |——.editorconfig
|   |——.gitgnore
|   |——index.html
|   |——package.json
|   |——README.md
#### 后台
> * Node(Express)
> * restful api
> * leancloud


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
