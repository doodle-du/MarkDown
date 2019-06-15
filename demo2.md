# Demo2

## 链接 demo

### 内嵌式链接
- 外部链接  
[百度](https://www.baidu.com)
- 内部链接1，链接仓库的其它文件：[demo](demo.md)
- 内部链接2，链接本文档的其它部分：[代码块demo](demo2.md#代码块-demo)

### 引用式链接
- 外部链接:[百度]
- 外部链接:[百度][baidu](添加别名)
- 内部链接1，链接仓库的其它文件：[demo]
- 内部链接2，链接本文档的其它部分：[代码块demo]

## 图片 demo

- 图片的MarkDown语法
![alt](url txt)
- 外部图片demo
![baidu](https://www.baidu.com/img/bd_logo1.png "baidu logo")
- **仓库内的图片demo**??
![](images/translate.png)

- 图片的引用式链接
- 外部图片demo
![baidu][baidu_logo]??
- **仓库内的图片demo**??
![][translate_png]


## 引用 demo

> 这是一个引用。

出自《...》

多次引用

>>>这是多重引文。

## 代码块 demo
- 行内代码
这个代码中用来声明变量`var a=2019`,控制台打印输出函数`console.log`输出变量`a`的值。
- 代码块
```javascript
var a= 2019;
console.log(a);
```
    var a= 2019;
    console.log(a);

<!--下面是本文档中用到的链接-->
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo]:demo.md
[代码块demo]:demo2.md#代码块-demo
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png "baidu logo"
[translate_png]: images/translate.png