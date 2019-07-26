### 一 黄色高亮文本的两种写法

1. 使用html标签的`<mark>高亮文字</mark>`  
<mark>我不知道怎么设置别的颜色的高亮，因为 html 的 style 属性和标签这里都不支持 有**知道**的求告知。</mark>    
2. 使用 `==高亮文字==`  
    ==黄色高亮文字==

---

### 二 文字的粗体，斜体，贯穿线，下划线
1. ~~贯穿线（中划线）~~
2. **粗体**
3. *斜体*
4. ***粗加斜***
5. ++下划线写法一使用`++`++
6. <u>下划线写法二使用html`<u>`标签</u>

---

### 三 `*`的用法  
一个`*`是无序列表，两个`**`是bold，只有三个`***`后不跟任何字符是分隔线，三个`***`后跟文字再跟三个`***`是粗加斜体。  
分隔线（水平线）是三个`-`或三个`*`。

---

### 四 代码块和行内代码   
代码块使用三个\`或者缩进4个空格。  
我现在还是用三个\`吧，毕竟不用缩进了  
行内代码使用\` \`包起来

Here is an example of C:

```c
#include <stdio.h>

int main()
{
/* 我的第一个 C 程序 */
printf("Hello, World! \n");

return 0;
}

```

Here is an example of C:

    #include <stdio.h>
    
    int main()
    {
    /* 我的第一个 C 程序 */
    printf("Hello, World! \n");
    
    return 0;
    }

---

### 五 blockquote区块引用，区块注释
有朋自远方来不亦乐乎
> 出自《论语》，这是对上面的话做的注释

---

### 六 标题
h1
===
h2
---

# h1
## h2
### h3
#### h4

---

### 七 超链接 图片链接
1. 行内式  
这是网址[github](https://www.github.com)  
这是QQ图片  
![github图片](https://raw.githubusercontent.com/bigweige/gitnote-images/master/gitnote/2019/07/26/QQ20190726-104350%402x-1564109063517.png)
2. 参考式  
这是网址[github][github]  
这是QQ图片  
![github图片][githubQQ]
3. 自动连接  
<https://www.github.com>  

[github]:https://www.github.com
[githubQQ]:https://raw.githubusercontent.com/bigweige/gitnote-images/master/gitnote/2019/07/26/QQ20190726-104350%402x-1564109063517.png

---

### 八 列表 
和后面的文字间必须有一个空格分开  

有序用1. 2. 3.
1. 列表1
2. 列表2
3. 列表3

无序列表用`*`或`-`号，   

* 无序列表
* 无序列表
* 无序列表

- 无序列表
- 无序列表
- 无序列表

---

### 九 任务列表 
- [ ] 待办
- [x] 已完成

---

### 十 脚注  
见底部脚注[^1]

---

### 十一 表格（table）
| 标题一 | 标题二 |
| :------- | :--: | 
| 内容左对齐| 内容居中对齐|
|----------------|--------------------|

---

### 十二 上下角标 
x^上角标^  
x~下角标~

---

### 十三 换行

在行尾添加两个空格加回车表示换行：  
这是一行后面加两个空格  
换行

---

### 十四 常用弥补Markdown的Html标签
#### 14.1 字体
<font face="宋体" color="red" size="4">字体及字体颜色和大小</font>   
<font color="#0000ff">字体颜色</font>

#### 14.2 换行
使用html标签`<br/>`换行

使用html标签<br/>换行

#### 14.3 文本对齐方式
<p align="left">居左文本</p>
<p align="center">居中文本</p>
<p align="right">居右文本</p>

---

[^1]:这是脚注1
