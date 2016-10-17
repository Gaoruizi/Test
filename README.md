README
===========================
该文件用来介绍如何运用代码及单元测试验证代码的正确性
****
###　　　　　　　　　　　　Author:Gao Ruizi
###　　　　　　　　　 E-mail:gaoruizi163@163.com

===========================

###[项目内容]
项目主体代码在src/main/java下play包，其中包含income类，generateSummary函数实现根据输入按格式输出收入功能，getDayOfWeek实现根据日期计算星期几的功能  
###[测试方法]
src/test/java下default包包含两大类，其中testMain类实现通过主函数验证输出的正确性，unitTest类实现通过单元测试验证输出的正确性  
具体测试方法如下：  
在String[] inputArray 静态数组中填写输入数据，处理数据的方法是income类下的generateSummary函数，主函数调用Income类下的方法或者进行单元测试  unitTest.java  
###[测试结果]
正确输出结果  
