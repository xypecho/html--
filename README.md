学习途中收藏的一些js代码以及一些个人笔记<br> 
===
1、var jq=jQuery.noConflict()，帮助您使用自己的名称（比如 jq）来代替 $ 符号。<br>
2、$(document).ready(function(){  });     当文档全部加载完运行，防止找不到对象<br>
3、animate可以变动标签的css属性   如需变动位置属性需先设置 position 属性设置为 relative、fixed 或 absolute！<br>
4、animate后面可以加函数，例：$("div").animate({top:"100px"},200,function(){alert(1)});   <br>
5、表格里面设置属性无需用style；例：<table width="700px" border="1px" <br>
6、三元运算符，即a?1:2;    如果a成立则返回1，如果不成立则返回2 <br>
7、table tr:nth-of-type(1){background: #ccc;}   设置表格第一行样式<br>
8、table tr:nth-child(2n){background-color: #ccc} 设置表格逢双数行时样式变动 <br>
9、vim命令模式到输入模式：i（在前面插入） a（在后面插入） o（换行插入） s（删除当前字符）  大写的iaso即作用于该行<br>
10、vim到末行模式：先到命令模式然后按 ：   末行模式下  x（保存并退出）<br>
11、圆形图片css    .round{width:100px;height:100px;border-radius:100px} <br>
12、当jquery里面的“$”函数和其他框架冲突时可以直接使用  jQuery来表示。例：	jQuery("h1").hide();  <br>
            <div style="background:gray"> 
            // $("h1,p").css({"fontSize":"13px"});    //组合选择器<br>
            // $("div h1").css({"color":"yellow"});        //后代选择器，选择div里面的所有h1标签<br>
            // $(".ft >h1").css({"color":"yellow"});    //子选择器，即class为ft的div里面的h1标签，不包括里面的div里面的h1<br>
            // $("div+h1").css({"color":"yellow"});   //div后面的一个h1标签<br>
            // $("div~h1").css({"color":"yellow"});       //div后面的所有h1标签<br>
            // $("h1:last").css({"color":"red"});        //最后一行<br>
            // $("h1:not(:first)").css({"color":"blue"});         //除了第一行的h1标签，其他都变色<br>
            // $("h1:even").css({"color":"blue"});         //偶数的h1标签变色,计算器语言序数从0开始<br>
            // $("h1:odd").css({"color":"blue"});      //奇数的h1标签变色,计算器语言序数从0开始<br>
            // $("h1:eq(2)").css({"color":"blue"});  //计算机语言里面的第2个h1标签样式变动<br>
            // $("h1:gt(2)").css({"color":"blue"});  //计算机语言里面大于第2个h1标签样式变动<br>
            //$("h1:lt(2)").css({"color":"blue"});  //计算机语言里面小于第2个h1标签样式变动<br>
13、</fieldset>标签可以设置一个区域的属性 例如<fieldset  disabled>   <br>
