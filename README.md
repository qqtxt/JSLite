JSLite
======
jQuery lite.

## 核心Core
```js
$$("#box")        //选择器
$$(fun)           //$$(fun) = $$(document).ready(function(){})
$$.extend         //通过源对象扩展目标对象的属性
$$.fn             //是一个对象，它拥有WCJ对象上所有可用的方法。
$$.isDocument     //判断对象是否为【document】
$$.isFunction     //判断对象是否为【函数】
$$.isObject       //判断是否为【Object】
$$.isArray        //判断对象是否为【数组】
$$.isContainsNode(parent,node)//parent是否包含node节点对象
$$.getUrlParam("param")         //获取url参数的值
$$.likeArray      //判断对象是否为数组或者是字符
$$.type           //获取类型
$$.map            //遍历集合中的元素返回一个新的数组，过滤null and undefined。
    //$$.map({"w":1,"c":2,"j":3},function(item,index){
    //     return index
    //}); 
$$.error          //创建自定义错误
$$.matches(element, selector) //如果当前元素能被指定的css选择器查找到,则返回true,否则返回false.
$$.sibling(elm,type)  //根据类型获取对象的集合
$$.inArray            //搜索数组中指定值并返回它的索引（如果没有找到则返回-1)
    //inArray(element, array, [fromIndex])
$$(document).ready(fun)//当页面dom加载完毕 “DOMContentLoaded” 事件触发时触发
$$("#box").each()     //遍历
$$("#box").map()      //遍历对象集合中的所有元素返回一个新的集合对象
$$("#box").get(1)     //当前对象集合中获取所有元素或单个元素
$$("#box").empty()    //对象集合中移除所有的dom子节点。
$$("#box").remove()   //删除【自己】及所有【自己】里面的内容
$$("#box").text()     //取得所有匹配元素的文本内容。
$$("#box").html()     //获取或设置对象内容。
$$("#box").css()      //获取或设置对象的style样式内容。
$$("#box").attr()     //读取或设置dom的属性。
$$("#box").offset()   //获取对象left|top|width|height
$$("#box").hasClass() //集合中是否有元素含有指定的class。
$$("#box").addClass() //为每个匹配的元素添加指定的class类名
$$("#box").removeClass() //清除集合中所有元素的指定class类名，不填写清空
$$("#box").toggleClass() //在匹配的元素集合中的每个元素上添加或删除一个或多个样式类
$$("#box").filter()   //筛选出与指定表达式匹配的元素集合。filter(selector) 
$$("#box").pluck()    //获取对象集合中每一个元素的属性值
$$("#box").find()     //后代节点的集合(可以带上滤选择器)
$$("#box").children() //获得每个匹配元素集合元素的直接子元素(可以带上滤选择器)
$$("#box").parent()   //对象集合中每个元素的直接父元素。
$$("#box").parents()  //获取对象集合每个元素所有的祖先元素（不包含根元素）
$$("#box").prev("div")//获取对象集合每个元素的所有上一个对象(可以带上滤选择器)
$$("#box").next("div")//获取对象集合每个元素的所有下一个对象(可以带上滤选择器)
$$("#box").prevAll()  //获取对此对象【上】所有兄弟对象(可以带上滤选择器)
$$("#box").nextAll()  //获取对此对象【下】所有兄弟对象(可以带上滤选择器)
$$("#box").siblings() //获取对此对象【其它】所有兄弟对象(可以带上滤选择器)
$$("#box").extend()   //扩展
$$("#box").bind()     //绑定事件
$$("#box").unbind()   //事件移除
$$("#box").before(content)      //:插入到标签开始前
$$("#box").prepend(content)     //:插入到标签开始标记之后
$$("#box").append(content)      //:插入到标签结束标记前
$$("#box").after(content)       //:插入到标签结束标记后
```


## 事件Event

## 异步请求Ajax

## Touch events