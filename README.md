# python_automation_demo
* 这个把selenium、monkey、接口代码写在了同一框架，共用一些方法或目录，分离整理如下：
* selenium(https://github.com/afantishui/selenium)
* monkey(https://github.com/afantishui/monkey)
* interface(https://github.com/afantishui/interface)

2017.9.5

* 基本完成网页操作 元素定位 执行用例 生成报告
* 注：HTMLTestRunner.py文件放在Python\Python\Lib目录下面（这是Python3的）

2017.9.7 

* 加入Excel操作

2017 9.15 

*  整合了接口自动化，自动发送邮件，生成Excel本地报告（lib interface文件夹）

2017/09/19 10:47 

* 优化了Excel本地报告样式

2017-09-29

* 把monkey压力测试框架整合进之前WEB/接口框架里面
* 1.已实现用例配置执行语句，bat启动脚本，生成测试报告 
* 2.后续要加入性能检测
* 优化需求：测试详情加入各类型事件比例，把报错信息也写入报告里面

2017-09-30

* 加入手机信息获取 内存 电量
