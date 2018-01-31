1、innerHTML虽非万维网标准，但是这个特性能访问元素内存储的所有内容

2、Document Object Model 文档对象模型DOM，提供访问和修改网页数据的标准化机制。

3、DOM视网页为关联节点的层次树，使用DOM改变网页内容的方案，需要移除元素下所有子节点，然后创建并附加上包含新内容的新子节点。

4、借由改变点的整份样式类，className节点特性达成戏剧性的样式变化

5、借由访问节点的单一样式特性，style节点特性达成少量样式变化

6、CSS样式类与JavaScript类完全无关，它们是完全不同的东西

7、网页元素可利用对象的visibility样式特性做动态的显示或者隐藏，演示特性display亦可达成相似的效果，display：none（隐藏）display：block（显示）。

8、利用document对象的createElement方法能够创建任何html元素，var decisionElem = document.createElement("p");

9、若需新增元素的文本内容，必须创建创建一个文本内容子元素，decisionElem.appendChild(document.createTextNode("new textarea !"));

10、借由小心的新增与移除DOM树上的节点，网页可以随意拆除与重组，document.getElementById("history").appendChild(decisionElem);
