### JavaScript页面加载完成后执行的事件

##### （1）原生JS方式

``` javascript
document.ready(){	//文档结构加载完成（不包括图片文字等）
    doSomeThing();
}

window.onload = function(){	//页面加载完成（包括图片文字等）
    doSomeThing();
}
```

##### （2）jQuery方式

```javascript
$(document).ready(function(){
    doSomeThing();
});
```

##### （3）jQuery简写方式

方式二的简写

```javascript
$(function(){
    doSomeThing();
});
```

