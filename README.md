# i塔内

## 关于本小程序
i塔内小程序为scnu师生提供电脑义务维修服务

## 插件、库
- [nodemailer](https://github.com/nodemailer/nodemailer) 云函数发送接单通知邮件
- [WxValidate](https://github.com/wux-weapp/wx-extend/blob/master/docs/components/validate.md) 微信小程序表单验证插件
- [Color UI](https://github.com/weilanwl/ColorUI)一个非常棒的样式及组件库，建议大家去使用一下

## 更新说明
- 1.6.0 
    - 第一个线上版本
    - 维修的基本流程已经完善，包括报单、接单、评价、总结等。此外还有申请身份认证、申请上下线、修改昵称等功能。以上功能能基本满义务维修过程的需求，数据展示、评价展示也已经完善。其它额外功能还需后续增加。
- 1.7.0
    - 新增订阅消息，报单完成后提醒机主评价
    - 优化了评价页和所有报单页的布局
- 1.7.3
    - 修复评价页的翻页错误
    - 修复昵称显示错误
    - 修改图标类名
- 1.8.0
    - 更新背景图片
    - 首页增加可修改的公告栏
    - 报单页显示总结
    - 使用分包，优化启动速度
    - 实验室增加了一些个人认为非常cooooooool的功能
- 1.9.0
    - 实验室增加NLP
    - 增加拒绝授权时的提醒
    - 我的报单增加返回首页，以解决订阅消息不回退页面的问题
    - 略微调整首页操作条图标的不对称性（还是没有完全对称）
- 1.9.1
    - 管理员可以取消报单
    - 修改getUserInfo相关代码
    - 优化成员显示，限制无效左滑
    - 增加历史报单数据、修机卡片
    - 使用基础库2.14.1
- 1.9.2
    - 增加了报单前的注意事项提醒
- 1.10.0
    - 增加修机问答、报修流程和使用说明
    - 禁止内部页面分享
    - 修复头像显示异常
    - 优化评价和报单翻页
    - 增加认证年份，优化人员展示方式
    - 适应userProfile接口更新，不再展示性别
- 1.10.1
    - 修复了一些已知问题


### 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

