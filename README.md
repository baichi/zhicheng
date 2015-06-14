# 项目日志

## 2015-06-14 22:27

* 添加事件处理机制，增设事件中心，观察者模式调度事件处理 -> event_center.js
* 为所有页面添加fastclick，解决移动端触摸延迟、点透等多种BUG，并在页面DOMContentLoaded初始化后添加
* 合并公共依赖的js文件为common.js一个文件
* 新增page/city，完成城市选择页面，点击城市增加选中效果等
* 新增page/service，完成驾管服务菜单页面，实现banner展示，完成菜单ui及点击跳转。
* 新增page/announce，完成交管局公告展示页面
* 新增page/commission，完成车务代办页面展示ui，包含banner展示和事务跳转功能

## 2015-06-14 16:59

* 本次增补6月13日工作进展情况
* 新增page/addcar，完成添加车辆页面ui，输入省份、车牌号、身份证号以及发动机号后保存添加
* 新增page/dispose，完成违章处理页面，含banner展示、领取优惠券、车辆认证、违章查询信息等信息，点击快速处理按钮进行违章处理操作
* 新增page/upload，完成图片上传模板页，其中包括上传前和上传完成两部分功能，逻辑部分未写
* 新增page/order，完成订单提交页面ui展示，展示内容包括违章信息及相关费用展示
* 新增page/handle，该页面为违章处理入口页，包含banner区，领取优惠券、添加车辆、车辆认证、违章查询等功能入口

## 2015-06-12 23:47

* 比较累，开发效率严重下降；需要自己照顾身体了，这是coding的本钱
* 今天工作量以页面为主，ui效果较多
* 新增page/query，编写查询页面，输入车牌号和身份证号等信息后提交查询
* 新增page/peccancy，违章查询结果页面的模板，其中包含查询到结果和未查询到两种情况，后端后续套用该模板展示即可
* 新增page/auth，完成车辆认证页面，其中链接部分需后续加上

## 2015-06-11 23:11

* 新增modal自定义弹框插件 static/js/modal目录下引用
* 新增page/register，编写注册页面
* 新增page/confirm，完成驾考信息确认页面，含返回和确认预约功能。
* 新增page/course，完成驾考科目选择页面，选择后应展示对应状态并提交选择的科目信息到后端，含逻辑demo。
* 新增page/select，完成选择考场页面，其中交互部分有demo示例。功能包含预约成功和失败。
* 新增page/wait，完成排队信息页面

## 2015-06-10 23:40

* 新增page/login，完成登录页面，登录提交信息功能未写逻辑
* 新增page/inform，完成驾考通知页
* 新增page/forget，完成预约驾考页模板，其中包括轮播图功能；该模板可包含忘记密码、未检测到信息、预约成功以及预约失败四种情况。
* 需要思考前端组件化的友好实现，目前公用部分资源存放于static各目录下。

## 2015-06-10 01:06

* 使用grunt搭建基础开发环境
* 使用less编写样式，实时解析成css
* 配置实时监听各文件修改，文件变化后，同步编译并输出到浏览器，无需刷新
* 引用基本文件，css的重置和基础响应式文件；js的有zepto fastclick modjs

