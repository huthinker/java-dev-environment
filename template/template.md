Node.js安装
===

![](../imgs/node.js.png)


> Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台， 用来方便地搭建快速的， 易于扩展的网络应用· Node.js 借助事件驱动， 非阻塞 I/O 模型变得轻量和高效， 非常适合 run across distributed devices 的 data-intensive 的实时应用·

Node.js的安装，请移步这里：

> [在 Windows、Mac OS X 與 Linux 中安裝 Node.js 網頁應用程式開發環境](http://www.gtwang.org/2013/12/install-node-js-in-windows-mac-os-x-linux.html)

安装完成这后，你可以在终端模式下检验一下：

```bash
$ node -v
v0.10.28
```

看到些提示，就表示你已成功安装上了`Node.js`。

Gitbook命令行速览
====

Gitbook是一个命令行工具，使用方法：

**本地预览**

```bash
$ gitbook serve ./图书名称
```

**输出一个静态网站**

```bash
$ gitbook build ./repository --output=./outputFolder
```

**查看帮助**

```bash
$ gitbook -h

  Usage: gitbook [options] [command]

  Commands:

    build [options] [source_dir] Build a gitbook from a directory
    serve [options] [source_dir] Build then serve a gitbook from a directory
    pdf [options] [source_dir] Build a gitbook as a PDF
    ebook [options] [source_dir] Build a gitbook as a eBook
    init [source_dir]      Create files and folders based on contents of SUMMARY.md

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

