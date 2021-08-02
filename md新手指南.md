# markdown新手指南
## 标题
* 在标题文字前加`#`就行，最多有**六**级标题，多少级标题就加多少个`#`
  >注：`#`和「标题」之间建议保留一个字符的空格，这是最标准的 Markdown 写法。
 
  ```
  # 一级标题
  ## 二级标题
  ### 三级标题
  #### 四级标题
  ##### 五级标题
  ###### 六级标题
  ```
## 列表
> 无序列表
  ```
  - 文本1
  - 文本2
  - 文本3
  ```
> 有序列表
```
1. 文本1
2. 文本2
3. 文本3
```
## 链接
> [百度](https://www.baidu.com)
  ``` 
  [百度](https://www.baidu.com)
  ```
## 图片
> ![皮卡丘](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fcdn.duitang.com%2Fuploads%2Fitem%2F201303%2F29%2F20130329205806_kTTnv.thumb.700_0.jpeg&refer=http%3A%2F%2Fcdn.duitang.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1629949851&t=f0f14593eb64498214ba44a4e359db97 '皮卡丘')
```
![图片alt](图片路径 '图片title')

```
> 图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
## 引用
> 在引用得文字之前加`>`
```
> 我是引用的文字1
>> 我是引用的文字2
>>> 我是引用的文字3
...
```
## 粗体
> **加粗文字**
```
**加粗文字**
```
## 斜体
> *斜体文字*
```
*斜体文字*
```
## 斜体粗体
***这是斜体加粗的文字***
```
***这是斜体加粗的文字***
```
## 删除线
~~这是加删除线的文字~~
```
~~这是加删除线的文字~~
```
## 分割线
****************************************
* 三个或者三个以上的 - 或者 * 都可以。
-----------------------------------------
## 代码引用
> 只有一行代码  用 ` 将语句**包**起来
  * ``
> 引用的语句为多行  可以将```置于这段代码的首行和末行。
## 表格

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
## 显示链接中带括号的图片
[1]:https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fcdn.duitang.com%2Fuploads%2Fitem%2F201303%2F29%2F20130329205806_kTTnv.thumb.700_0.jpeg&refer=http%3A%2F%2Fcdn.duitang.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1629949851&t=f0f14593eb64498214ba44a4e359db97
![][1]
```
[1]:https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fcdn.duitang.com%2Fuploads%2Fitem%2F201303%2F29%2F20130329205806_kTTnv.thumb.700_0.jpeg&refer=http%3A%2F%2Fcdn.duitang.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1629949851&t=f0f14593eb64498214ba44a4e359db97
显示图片：![][1]
```
## 流程图
flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```

