# Log

20171129
1. 所有代码重新整理
2. 将工具库移动到: https://github.com/hunterhug/parrot
3. 项目改名
4. 增加栗子

20170717
1. 增加示例
2. 增加环境说明

20170621
1. 增加hbase
2. 增加cassnadra
3. 增加图片切割库等
4. 增加新库后第三方依赖请自行添加
5. 新增DELETE/PUT方法和其他HTTP方法:OtherGo(method, contenttype string)

`contenttype`：
```
	HTTPFORMContentType = "application/x-www-form-urlencoded"
	HTTPJSONContentType = "application/json"
	HTTPXMLContentType  = "text/xml"
	HTTPFILEContentType = "multipart/form-data"
```

20170616
1. 增加xorm存储

20170527
1. 增加说明
2. 默认不带UA
3. 自动增加Host头部
 
20170515
1. 增加无cookie API爬虫NewAPI()
2. API爬虫可以用来对接各大API

20170513
1. 补充说明
2. 呼喊需求！！

20170405
1. 简单就是美
2. 核心功能完成
3. 示例转移到另外的仓库

20170404
1. 增加存储库redis和mysql
2. 优化

20170330
1. 抽离SpiderConfig出来，重构解耦，链式配置可直接传SpiderConfig，默认逐链覆盖
2. POST之后获取JSON数据可能被编码成\u9a8c，增加JsonToString爬虫对象方法获取数据
3. 例子重构

20170329

1. 增加默认爬虫
2. 单只爬虫加锁

20170319

1. 新增多User-Agent全局变量，默认支持几百个浏览器标志
2. 增加随机User-Agent函数，可以随机提取一个标志
3. 新增多浏览器池Pool，可以模拟若干个浏览器

20170318

1. 新增glide管理第三方库
2. 更新若干函数
3. 修改README.md等
4. 增加基础实例
5. 增加任意图片下载示例（淘宝有特殊处理）
6. 知乎登陆
