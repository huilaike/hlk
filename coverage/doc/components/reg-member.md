``` js
// 接口数据
{
    "optName":"glg1",
    "shopId":288881,
    "parentShopId":288880,
    "name":"test", // 姓名
    "mobile":"1101", // 手机号
    "sex":"F", // 性别
    "birthday":"", // 生日日期
    "birthType":0, // 阴阳历
    "sourceId":1, // 来源
    "page":"", // 备注
    "introducerid":null, // 备注id
    "token":"47c331d5-4003-40e3-a82a-03be2786a73b"
}

// 逻辑处理：
// 涉及到日期组件和数字组件
// 必填字段校验，
// 提交loading
```
#### 属性
| 属性 | 说明 | 类型 | 默认值
| -- | -- | -------------- | -- 
| ispop | 是否弹窗 | boolean | false
| member-info | 会员卡信息: 扩展可拷贝会员卡 | object | {}
| width | 宽 | string | --
| height | 高| string | --

#### 事件
| 事件名称 | 说明 | 回调参数
| -- | -- | -- 
| callback | 创建成功回调 | object 会员卡信息