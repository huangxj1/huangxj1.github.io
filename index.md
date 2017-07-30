---
layout: default
---

## [](header-2)Markdown 语法

Markdown 是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。

### [](hearder-3)标题

在Markdown中，共有六级标题，在标题的前面加上相对应数量的#号和一个空格即可。

```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

### [](hearder-3)列表

有序列表只需要在文字前面加上星号、加号或减号即可变成无序列表，有序列表则直接在文字前加1. 2. 3. 符号和文字之间依然要加一个空格。

```
* 1
* 2
* 3
1. 1
2. 2
3. 3
```

代办列表

```
- [ ] 不勾选
- [×] 勾选
```

### [](header-3)引用

如果你需要引用一段别处的句子，那么就要用引用的格式。

```
> 一级引用
>> 二级引用
```

### [](header-3)图片与链接

插入图片的语法为：

```
![图片说明](图片路径或链接)
```

插入链接语法为：

```
[链接说明](链接的url)
```

或者直接用< >将网址或者邮箱放在中间，也能将地址直接转成链接。

### [](header-3)代码

只要把你的代码块包裹在 ``` 之间，你就不需要通过无休止的缩进来标记代码块了。 在围栏式代码块中，你可以指定一个可选的语言标识符，然后我们就可以为它启用语法着色了。 举个例子，这样可以为一段 Ruby 代码着色：

```ruby
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
```

### [](header-3) 强调

在Markdown中，可以使用 * 和 _ 来表示斜体和加粗。

斜体：

```
*Coding，让开发更简单*
_Coding，让开发更简单_
```

加粗：

```
**Coding，让开发更简单**
__Coding，让开发更简单__
```

### [](header-3)表格

例如：

```
head1        | head two          | three 
-------------|-------------------|-------
ok           | good swedish fish | nice  
out of stock | good and plenty   | nice  
ok           | good `oreos`      | hmm   
ok           | good `zoute` drop | yumm  
```

效果如下：

| head1        | head two          | three |
|--------------|-------------------|-------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### 分割线

用--- 独占一行生成

***

### 感谢

本文参考：[Markdown——入门指南 by Te_Lee](https://coding.net/help/doc/project/markdown.html)

