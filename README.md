# No.wan
markdown语法：
> 标题类
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

> 加粗：要加粗的文字左右分别用两个*号包起来
**这是加粗的文字**

> 斜体: 要倾斜的文字左右分别用一个*号包起来
*这是倾斜的文字*

>斜体加粗: 要倾斜和加粗的文字左右分别用三个*号包起来
***这是斜体加粗的文字***

> 删除线: 要加删除线的文字左右分别用两个~~号包起来
~~这是加删除线的文字~~

> 引用：在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>
```
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容
```
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容

### 分割线
三个或者三个以上的 - 或者 * 都可以。
```
---
----
***
*****
```
---
----
***
*****

### 图片
```
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```
![logo](https://github.com/chirilingfeng/No.wan-doc/tree/master/img/logo.jpg)

### 超链接
```
[超链接名](超链接地址 "超链接title")
title可加可不加
eq:
[简书](http://jianshu.com)
[百度](http://baidu.com)
```
[简书](http://jianshu.com)
[百度](http://baidu.com)

注：Markdown本身语法不支持链接在新页面中打开，貌似简书做了处理，是可以的。别的平台可能就不行了，如果想要在新页面中打开的话可以用html语言的a标签代替。

### 列表

#### 无序列表
```
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格
```
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格

#### 有序列表
```
1.列表内容
2.列表内容
3.列表内容

注意：序号跟内容之间要有空格
```
1.列表内容
2.列表内容
3.列表内容

#### 列表嵌套
**上一级和下一级之间敲三个空格即可**
- 列表内容

1.列表内容
2.列表内容
3.列表内容

+ 列表内容

1.列表内容
2.列表内容
3.列表内容

### 表格
```
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略

eq: 
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
```
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
