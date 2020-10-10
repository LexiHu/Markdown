# Markdown 基本语法总结
## 一、标题
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
## 二、列表
### 1.无序列表
#### 语法：用 - + * 任何一种都可以，
效果如下：
- 列表内容
- 列表内容
- 列表内容
### 2.有序列表
#### 语法：数字加点
效果如下：
1. 列表内容
2. 列表内容
3. 列表内容

注意：序号跟内容之间要有空格
## 三、字体
- 加粗
文字左右分别用两个星号包起来，**加粗**
- 斜体
文字左右分别用一个星号包起来，*斜体*
- 斜体加粗
文字左右分别用三个星号号包起来，***斜体加粗***
- 删除线
要加删除线的文字左右分别用两个波浪线号包起来，~~删除线~~
## 四、引用
在引用的文字前加>即可。
效果如下：
> 一盏灯， 一片昏黄； 一简书， 一杯淡茶。 守着那一份淡定， 品读属于自己的寂寞。 保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。
## 五、分割线
三个或三个以上-或星号都可以

---
***
## 六、插入
### 1. 插入图片
语法：![图片alt](图片地址 ''图片title'')
图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加。
效果如下：
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")
### 2. 插入超链接
[显示文本](链接地址)
例如：[简书](http://www.jianshu.com)
## 七、表格
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

注意：
- 第二行用来分割表头和内容。
- 有一个-就行，为了对齐，多加了几个
- 文字默认居左
- 两边加：表示文字居中
- 右边加：表示文字居右
## 八、代码引用
### 1. 单行代码
代码之间分别用一个反引号包起来

    `代码内容`
    `create database hero;`
    
### 2. 代码块
代码之间分别用三个反引号包起来，且两边的反引号单独占一行

 ```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```

注：为了防止转译，前后三个反引号处加了小括号，实际是没有的。这里只是用来演示，实际中去掉两边小括号即可。
