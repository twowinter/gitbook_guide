
# 第1.2节 常用操作
---

这节就两个操作，创建和预览，这是我们最常用的操作。

## 1 书本创建

### 1.1 gitbook官方模版

> $ gitbook init

通过这个命令就会在当前目录下创建gitbook的模版，目录如下：

```
├── README.md
└── SUMMARY.md
```

README.md 是介绍页。  
SUMMARY.md 是目录页。

### 1.2 我的模版

增加了章节目录结构以及图片目录，方便大家快速上手，同时也对目录结构做了个规范。

```
│  README.md
│  SUMMARY.md
│  
├─chapter
│      1.md
│      1_1.md
│      1_1_1.md
│      1_2.md
│      2.md
│      2_1.md
│      2_2.md
│      markdown.md
│      
└─img
        monkey.bmp
```

## 2 书本预览

在已有内容的目录下，使用如下命令可以得到一个页面，浏览器访问 http://localhost:4000 即可看到。

> $ gitbook serve

在已有内容的目录下，使用如下命令可以得到一个本地静态页面，它位于新生成的目录 \_book\ 下。

> $ gitbook build


## 3 windows下的操作技巧

windows下大家不是要调用命令在进到书本目录下吗?比较繁琐点。

快速的操作是直接在目录下右键，选择 git bash here，没有安装 git 的赶紧装起来。

![](/img/1_2/gitbook_op_windows_gitbash.png)

在 gitbash 中即可操作 gitbook 命令。

![](/img/1_2/gitbook_op_serve.png)