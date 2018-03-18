# ling_learn_more
this is my study program 
## 重新创建的项目 没有为什么就是将技术尽量的使用自己的话总结出来.
### 首先就是 关于节点的操作 
* 增删改查
> 先是查吧
```js
document.getElementById();//根据id，IE6、7中会把表单元素的name当做ID值获取，多个id存在只获取第一个，也就是最先出现的哪一个，没有找到返回nul
document.getElementsByTagName();//根据标签名，返回值是一个类数组，没有找到返回空数组，IE8以及以前版本不兼容。
document.getElementsByClassName();//根据类名
document.getElementsByName();//根据名,返回值是一个类数组，没有找到返回空数组,主要是获取input标签上的数据
document.querySelector();//返回值只获取到一个元素
document.querySelectorAll();//返回值获取数组
//查找父元素
parentNode;//父节
parentElement;//父元素节点
offsetParent;//一般是body

//查找子元素
childNode//获取文本
childElement//获取节点
children//获取子节点,返回数组
fristChild//获取第一个节点
fristChildElement;//获取节点
lastChild//获取最后一个节点
 
//查找兄弟节点
previousElementSibling()
nextElementSibling()
parentElement.children[1];


//使用jquery查找
$("");
$("").eq();
$("").find();
$("").parent();
$("").siblings();




```
