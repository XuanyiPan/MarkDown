# Demo2



## 链接 demo

### 内嵌式链接

-外部链接:[百度](http://www.baidu.com)  
-内部链接1，链接仓库的其他文件: [demo1.md]()  
-内部链接2，链接本文档的其他部分: [代码块](demo2.md#代码块-demo)  

### 引用式链接  

- 外部链接:[百度]  
- 外部链接:[百度][baidu]
- 内部链接1，链接仓库的其他文件: [demo1.md]()  
- 内部链接2，链接本文档的其他部分: [代码块 demo]



## 图片 demo

- 图片的MarkDown语法  
  ![alt](url text)


- 外部图片 demo
![baidu](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1503205542450&di=544515d3b679b25f5db2b9e9843c8843&imgtype=0&src=http%3A%2F%2Fwww.qiuyongsheng.com%2Fstatic%2Findex%2Fbaidu.jpg "百度图片")  

- 仓库内的图片  
![linux_hha](images/linux_hha.jpg)

图片的引用式链接
- 外部图片 demo
![baidu][baidu_logo]


## 引用demo

> 这是一个引文。
  
————出自《出处》

多重引用。
>>> 这是多重引文。



## 代码块 demo

- 行内代码

这个代码中用来声明变量是`var a = 10` ,打印变量内容是 `console.log`函数的调用。


-块式代码
```javascript

var a =10;
cconsole.log(a);

```

    var a =10;
    cconsole.log(a);




<!--- 下面是本文档中用到的链接 -->
[百度]: http://www.baidu.com  
[baidu]:http://www.baidu.com  
[demo1]:demo1.md
[代码块 demo]:demo2.md#代码块-demo

[baidu_logo]:https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1503205542450&di=544515d3b679b25f5db2b9e9843c8843&imgtype=0&src=http%3A%2F%2Fwww.qiuyongsheng.com%2Fstatic%2Findex%2Fbaidu.jpg 
