学习途中收藏的一些js代码以及一些个人笔记<br>
1、var jq=jQuery.noConflict()，帮助您使用自己的名称（比如 jq）来代替 $ 符号。<br>
2、$(document).ready(function(){  });     当文档全部加载完运行，防止找不到对象<br>
3、animate可以变动标签的css属性   如需变动位置属性需先设置 <b>position</b> 属性设置为 relative、fixed 或 absolute！<br>
4、animate后面可以加函数，例：$("div").animate({top:"100px"},200,function(){alert(1)});   <br>
5、表格里面设置属性无需用style；例：<table width="700px" border="1px" <br>
6、三元运算符，即a?1:2;    如果a成立则返回1，如果不成立则返回2 <br>
7、table tr:nth-of-type(1){background: #ccc;}   设置表格第一行样式<br>
8、table tr:nth-child(2n){background-color: #ccc} 设置表格逢双数行时样式变动 <br>
9、vim命令模式到输入模式：i（在前面插入） a（在后面插入） o（换行插入） s（删除当前字符）  大写的iaso即作用于该行<br>
10、vim到末行模式：先到命令模式然后按 ：   末行模式下  x（保存并退出）
