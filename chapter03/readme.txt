1、浏览器窗口与客户端窗口，客户端窗口加标题栏、工具栏及滚动条等于浏览器窗口。客户端窗口提供较佳的图像尺寸调整基准，不同的平台与不同的厂商造成浏览器窗口尺寸差异。

2、网页上所有元素都有一个style对象，借此可以得到网页上任何元素的宽度和高度。

3、setTimeout()函数创建单次定时器，该定时器将于一段时限后触发js代码。

4、设定依固定间隔启动的定时器，使用setInterval（）创建间隔定时器。

5、以毫秒millisecond为指定定时器时限单位，1毫秒为千分之一秒。

6、网页具有设定样式style对象，height、width都是样式。

7、客户端窗口是浏览器窗口的一部分，只负责呈现网页，其它不关它的事，可以通过document对象的body.clientWidth和body.clientHeight特性获得客户端窗口的宽和高。例如：document.getELementById("rockImg").style.height=(document.body.clientHeight-100)*0.9

8、onresize函数和onclick函数是用户触发，而onload函数不然。调整浏览器窗口尺寸将触发onresize

9、js于浏览器关闭或者网页重新载入时摧毁所有变量。

10、cookie是浏览器存储在用户计算机里的一块数据，只不过当关闭浏览器、重新载入网页、关闭计算机时，cookie依然在你的计算机里（硬盘里），故cookie成了存储用户名称的便利选择。

11、JavaScript代码，cookie代码：适合客户端，便利的持久性，数据存储方案

12、cookie以独一无二的名称存储一段数据，类似变量，但是和变量不同的是它需要设定有效日期expiration date，实际上，cookie并非真的永恒不变，它们只是比变量的寿命更长。一般调用cookie方法：读取readCookie("name")，写入writeCookie("name","value","expiration date");最好别将敏感数据存到cookie里。

13、cookie通常存储于硬盘上，但它无权碰触硬盘上的其他东西，cookie不是可执行程序，cookie是.js文件，不会传播病毒和蠕虫，cookie能够存储个人数据，但用户必须特意上网输入数据。

14、各个浏览器负责维护自己独有的cookie数据库，不同浏览器不能共享cookie数据。

15、cookie只适用于存储相对较少的文本数据，一般来说少于4Kb，并且cookie效率不高。每个cookie都有有效期，超过期限，浏览器将清除cookie值。

16、查看浏览器是否支持cookie：navigator.cookieEnable.



