---
title: js文件的写法
date: 2021-03-09 08:54:12
tags:
    - 前端
categories: 前端
---
```javascript
(function(owner){
	owner.btn=function(){
		alert("aaa");
	}
}(window.test={})) //test是js的文件名
```
