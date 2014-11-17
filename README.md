#AutoCS

一个辅助用户搜索的js插件，只有3K大小。

在HTML页面文本框内输入搜索内容时自动提示关键字或搜索结果。

[View Demo](http://rawgithub.com/wordgold/autocs/master/demo.html)

****************************************

###使用方法

这是一个jquery插件，使用方法：

```js
	$("Selectors").autocs("url");
```

由于表现和逻辑分离，使用前请自行导入或修改 **autocs.css** 文件内容。

**为防止IE6崩溃，请在页面加载完毕后执行。**

```js
	$(function(){
		$("Selectors").autocs("url");
	});
```

****************************************

###代码讲解

[邮箱输入辅助插件 AutoCS](http://yu123.me/2013/04/autocs/)