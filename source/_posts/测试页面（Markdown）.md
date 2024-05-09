---
title: 测试页面（Markdown）
tags:
  - 测试
categories:
  - 测试
  - Markdown
abbrlink: 37a72b3e
# cover: https://i.loli.net/2020/05/01/gkihqEjXxJ5UZ1C.jpg
date: 2022-06-18 18:04:39
---

## 标题

使用`#`来设置标题，有多少个`#`就是第多少级标题

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

<!-- endtab -->

<!-- tab 预览  -->

见本文中的标题

<!-- endtab -->

{% endtabs %}

## 字体效果

原版中共有3种字体效果：加粗、倾斜、删除，可以相互叠加

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
**这是加粗的文字**
*这是倾斜的文字*
***这是斜体加粗的文字***
~~这是加删除线的文字~~
~~*这是斜体删除的文字*~~
```

<!-- endtab -->

<!-- tab 预览  -->

**这是加粗的文字**

*这是倾斜的文字*

***这是斜体加粗的文字***

~~这是加删除线的文字~~

~~*这是斜体删除的文字*~~

<!-- endtab -->

{% endtabs %}

## 引用

使用`>`添加引用效果，允许嵌套

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
> 这是引用的内容
```

<!-- endtab -->

<!-- tab 预览  -->

> 这是引用的内容

<!-- endtab -->

{% endtabs %}

## 列表

列表允许嵌套

### 无序列表

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
- 内容1
- 内容2
- 内容3
```

<!-- endtab -->

<!-- tab 预览  -->

- 内容1
- 内容2
- 内容3

<!-- endtab -->

{% endtabs %}

### 有序列表

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
1. 内容1
2. 内容2
3. 内容3
```

<!-- endtab -->

<!-- tab 预览  -->

1. 内容1
2. 内容2
3. 内容3

<!-- endtab -->

{% endtabs %}

## 分割线

三个或者三个以上的`-`或者`*`都可以

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
---
```

<!-- endtab -->

<!-- tab 预览  -->

---

<!-- endtab -->

{% endtabs %}

## 链接

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
[百度](https://www.baidu.com/)
```

<!-- endtab -->

<!-- tab 预览  -->

[百度](https://www.baidu.com/)

<!-- endtab -->

{% endtabs %}

## 图片

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
<!-- ![](https://www.nickxu.top/static/favicon.jpg) -->
![](/images/my_avatar.jpeg)
```

<!-- endtab -->

<!-- tab 预览  -->

<!-- ![](https://www.nickxu.top/static/favicon.jpg) -->
![](/jinheyong/images/my_avatar.jpeg)
![](/jinheyong/images/cover/cover10.jpg)
<!-- endtab -->

{% endtabs %}

## 表格

Markdown 制作表格使用`|`来分隔不同的单元格，使用`-`来分隔表头和其他行

自定义对齐方式：

- `-:`内容和标题栏居右对齐

- `:-`内容和标题栏居左对齐

- `:-:`内容和标题栏居中对齐

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
```

```markdown
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

<!-- endtab -->

<!-- tab 预览  -->

| 表头   | 表头   |
| ------ | ------ |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 单元格 | 单元格 |  单元格  |
| 单元格 | 单元格 |  单元格  |

<!-- endtab -->

{% endtabs %}

不建议自己来敲，`Typora`自带插入表格，而且也有很多[在线表格生成网站](https://www.tablesgenerator.com/markdown_tables)

## 代码

### 行内代码

{% tabs  样例%}

<!-- tab 代码  -->

```markdown
在C++中如果要使用`cin`或者`cout`，应当先设置命名空间，如：`using namespace std;`
```

<!-- endtab -->

<!-- tab 预览  -->

在C++中如果要使用`cin`或者`cout`，应当先设置命名空间，如：`using namespace std;`

<!-- endtab -->

{% endtabs %}

### 代码块

{% tabs  样例%}

<!-- tab 代码  -->

````markdown
```cpp
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello World!";
    return 0;
}
```
````

<!-- endtab -->

<!-- tab 预览  -->

```cpp
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello World!";
    return 0;
}
```

<!-- endtab -->

{% endtabs %}

