# 华天旅游网会员中心子系统

## 1. 架构
- 采用avalon 1.5版MVVM框架+后台JSON数据接口实现功能
- 页面采用单一页面+avalon模板方式组成


## 2. 接口

### 2.1 用户账单接口
参数只有userid一个
```javascript
http://www.htyou.com/user/htuser_getTourOrderDetail.action?userid=637478
```


## 3. 访问地址
```http://www.htyou.com/page/usercenter/index.htm```


## 4. 订单页面按照：全部订单 未付费 已付费 已结算 分类（有个要接口出来后才有，先做已经有的）