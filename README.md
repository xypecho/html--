学习途中收藏的一些js代码以及一些个人笔记<br>
1、var jq=jQuery.noConflict()，帮助您使用自己的名称（比如 jq）来代替 $ 符号。<br>
2、$(document).ready(function(){  });     当文档全部加载完运行，防止找不到对象<br>
3、基本选择器
<!DOCTYPE html>
<html>
<head>
	<script type="text/javascript"  src="jquery-1.8.3.min.js"></script>
</head>
<body>
	<div  id="first">	
		<h2>hello world</h2>
		<h2>你好，世界</h2>

		<div  id="second">
			<h2>i like java</h2>
			<h2>我爱java</h2>

		</div>


	</div>

	<h2>今天星期天</h2>
	<h2>今天星期一</h2>
</body>
	<script type="text/javascript">
		// $("#first>h2").css({"color":"purple"});    //表示子元素即第一个div下面的h2标签
		// $("#first+h2").css({"color":"purple"});   //+号表示除了first 的div外加div外面的  ！一个    h2标签
		// $("#first~h2").css({"color":"purple"});   //+号表示除了first 的div外加div外面的  ！所有    h2标签
		// $("h2:first").css({"color":"purple"});	//第一个h2标签的css变动
		// $("h2:last").css({"color":"purple"});	//最后一个h2标签的css变动
		// $("h2:not(:first)").css({"color":"purple"});    //除了第一个h2标签其他的css都变
		// $("h2:even").css({"color":"blue"});      	//偶数的h2的css变动     ps机器语言从0开始计数
		// $("h2:odd").css({"color":"green"});	//奇数的h2的css变动		  ps机器语言从0开始计数
		// $("h2:eq(2)").css({"color":"orange"});  //第二个h2标签的css变动     ps机器语言从0开始计数
		// $("h2:gt(1)").css({"color":"yellow"});    //大于1的h2标签的css变动  	ps机器语言从0开始计数
		$("h2:lt(1)").css({"color":"yellow"});    //小于1的h2标签的css变动  	ps机器语言从0开始计数
	</script>
</html>
