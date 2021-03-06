---
　　layout: post
　　title: 新的测试
---

## 欢迎使用 Markdown ##

### 区块元素 ###

#### 段落和换行 ####

#### 标题 ####
在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶，例如：

<pre>
# 这是 H1
## 这是 H2
###### 这是 H6
</pre>

#### 区块引用 Blockquotes ####
看起来像是你自己先断好行，然后在每行的最前面加上 <code>></code> ：
**先来代码效果**  
<pre>
再加一行  
行的后面要加2个空格才可以换行 
>在整个段落的第一行最前面加上 >
>>还可以嵌套
</pre>
>这里看是显示效果  
再加一行  
行的后面要加2个空格才可以换行  
>在整个段落的第一行最前面加上 <code>></code>
>>还可以嵌套


引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等：
<pre>
> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。
> 
> 给出一些例子代码：
> 
>     return shell_exec("echo $input | $markdown_script");
</pre>
#### 列表 ####
Markdown 支持有序列表和无序列表。

无序列表使用星号、加号或是减号作为列表标记：  
**先来代码效果**    
<pre>
--- 
* *号列表标记
 * *  号后面要跟上空格或制表符
* 列表通过空格进行嵌套操作  

---
+ 列表标记
 + +号后面要跟上空格或制表符
 + 列表通过空格进行嵌套操作
+ +号下面怎么多出来了一行，搞不懂，弄了一个分隔线，现在就没有了

---
     
- 减号也会多出来一行，这是为什么呢
- Green
- Blue

**有序列表**  

1.  使用数字接着一个英文句点  
1.  数字不需要有顺序  
1.  建议第一个项目最好还是从 1. 开始
2.  那我每个都用1.方便一些

---

*   这是一个有缩进的列表，   
    我写不到一行怎么办呢，   
    只能多写几个字做出这种效果来   
*   勉强写出两行字

---
*    做一个有多个段落的列表，每个项目下的段落都必须缩进 4 个空格或是 1 个制表符：    
    原来如此
*    再加一项，区别出来效果
</pre>   
**再来显示效果，编辑的时候为什么要多一个空行，不空一行不出来效果？**
    
--- 
* *号列表标记
 * *  号后面要跟上空格或制表符
* 列表通过空格进行嵌套操作  

---
+ 列表标记
 + +号后面要跟上空格或制表符
 + 列表通过空格进行嵌套操作
+ +号下面怎么多出来了一行，搞不懂，弄了一个分隔线，现在就没有了

---
     
- 减号也会多出来一行，这是为什么呢
- Green
- Blue

**有序列表**  

1.  使用数字接着一个英文句点  
1.  数字不需要有顺序  
1.  建议第一个项目最好还是从 1. 开始
2.  那我每个都用1.方便一些

---

*   这是一个有缩进的列表，   
    我写不到一行怎么办呢，   
    只能多写几个字做出这种效果来   
*   勉强写出两行字

---
*    做一个有多个段落的列表，每个项目下的段落都必须缩进 4 个空格或是 1 个制表符：    
    原来如此
*    再加一项，区别出来效果

---
*  再来一个项目里面有引用的
      > 那 > 就需要缩进  
      > 引用的缩进就要加 8 个空格或是 2 个制表符  

* 再加一项看看代码块    
        说是加8个空格