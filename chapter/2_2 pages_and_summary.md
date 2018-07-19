
# 第2.2节 目录页和普通页

## 1 目录页

SUMMARY.md 就是各个页面的链接总和。

### 1.1 简单示例

```
# Summary

* [Part I](part1/README.md)
    * [Writing is nice](part1/writing.md)
    * [GitBook is nice](part1/gitbook.md)
* [Part II](part2/README.md)
    * [We love feedback](part2/feedback_please.md)
    * [Better tools for authors](part2/better_tools.md)
```

### 1.2 内容锚点

不仅仅可以展示不同的子章节，还能在目录中链接到章节内的锚点。

```
# Summary

### Part I

* [Part I](part1/README.md)
    * [Writing is nice](part1/README.md#writing)
    * [GitBook is nice](part1/README.md#gitbook)
* [Part II](part2/README.md)
    * [We love feedback](part2/README.md#feedback)
    * [Better tools for authors](part2/README.md#tools)
```

### 1.3 内容 Parts

目录可以分出几个大的部分，由标题或水平线分隔：

```
# Summary

### Part I

* [Writing is nice](part1/writing.md)
* [GitBook is nice](part1/gitbook.md)

### Part II

* [We love feedback](part2/feedback_please.md)
* [Better tools for authors](part2/better_tools.md)

----

* [Last part without title](part3/title.md)
```

## 2 普通页

gitbook 默认是采用了 Markdown 的语法。

这是章节示例，在模版中('/chapter/markdown.md')也有一个全面的 markdown 语法展示文件。

```
# Title of the chapter

This is a great introduction.

## Section 1

Markdown will dictates _most_ of your **book's structure**

## Section 2

...
```