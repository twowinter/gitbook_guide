
# 第2.1节 目录结构

如果已经采用[1.2 常用操作](/1_2 basic_op.md)提到的目录模版，那么这一节可能就用不到了。

不过也可以做个了解。

## 1 目录结构介绍

通常，我们看到的gitbook项目都是这样的:

```
.
├── book.json
├── README.md
├── SUMMARY.md
├── chapter-1/
|   ├── README.md
|   └── something.md
└── chapter-2/
    ├── README.md
    └── something.md
```


- book.json	
用于存储项目的一些配置。(可选的)

- README.md	
封面页 / 介绍页。(必须的)

- SUMMARY.md
内容目录。(可选的)

- GLOSSARY.md
术语。(可选的)