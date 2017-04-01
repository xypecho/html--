学习途中收藏的一些js代码以及一些个人笔记<br>
1、var jq=jQuery.noConflict()，帮助您使用自己的名称（比如 jq）来代替 $ 符号。<br>
2、$(document).ready(function(){  });     当文档全部加载完运行，防止找不到对象<br>
3、animate可以变动标签的css属性   如需变动位置属性需先设置 <b>position</b> 属性设置为 relative、fixed 或 absolute！<br>
4、animate后面可以加函数，例：$("div").animate({top:"100px"},200,function(){alert(1)});   <br>
