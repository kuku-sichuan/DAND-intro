## Markdown基本用法
编辑markdown所有标记符时，一定要切换到**英文输入**。灰色区域是代码，紧接着就是效果显示。
### 常用的文字编辑
**Hint**：下面的#和文字之间有一个_空格_.有几个#就是几级标题啦，最多６级。
```markdown
# 一级标题
## 二级标题
```
# 一级标题　
## 二级标题
**Hint**：文字突出的各种方法。
```markdown
*突出１*
***突出2**
**突出3***
_突出4_
__突出5__
___突出6___
```
*突出１*  
**突出2**  
***突出3***  
_突出4_  
__突出5__  
___突出6___  
**Hint**：换行的２种方法：段落间换行`<p><p>`;段落内换行`<br /><br />`br与/之间有一个空格; 
```markdown
<p>这是一个<p>换行
<br />这是<br />一个<br />换行
这是一个　　
换行。
```
<p>这是一个<p>换行
<br />这是一个<br />换行　　

## 超文本编辑
**Hint**:图片插入,可以将图片与当前文件放置在同一目录下，也可以采用完整地址。如果地址无效，就出显示出[]里的信息。
```markdown
![好好学习]()
![好好学习](good_study.jpeg)
```
![好好学习]()

![好好学习](good_study.jpeg)

**Hint**:链接插入可以采用两种方式。
```markdown
https://classroom.udacity.com
[Udacity](https://classroom.udacity.com)
```
https://classroom.udacity.com  
[Udacity](https://classroom.udacity.com)

**Hint**:列表编辑分为两种一种是无序编辑(标识符有`*`,`+`,`-` )，一种是有序编辑(标识符有`1.`)，*标识符和内容之间都有空格，换点用Enter*。

```markdown
* 无序1.1
* 无序1.2
- 无序2.1
- 无序2.2
+ 无序3.1
+ 无序3.2
1. 有序１
2. 有序２ 
```
* 无序1.1
* 无序1.2


- 无序2.1
- 无序2.2


+ 无序3.1
+ 无序3.2


1. 有序１
2. 有序２

**Hint**:代码的插入也有两种：一种是插入代码块(双引号之间的为真实代码，*｀*不是单引号而是左上角的~键)，一种是在文字中内联代码
```markdown
                       "
```python
import numpy as np
import pandas as pd


number=15
```                    "

`data_frame`
`Shanghai`
```
```python
import numpy as np
import pandas as pd


number=15
```  
`data_frame`  
`Shanghai`  

## 补充
### 表格编辑
```markdown
| name1 | name2 | name3 |name4|
|  :---:  | :---: | :---: |:---:|
| A     |   B   |  C    |  D  |
| a     |   b   |  c    |  d  |
```
| name1 | name2 | name3 |name4|
|  :---:  | :---: | :---: |:---:|
| A     |   B   |  C    |  D  |
| a     |   b   |  c    |  d  |　　

更多资料：https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


