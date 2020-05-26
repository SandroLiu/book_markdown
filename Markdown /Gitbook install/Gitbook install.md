# Gitbook 使用

&emsp;&emsp;Gitbook可以通过Gitbook editor应用使用也可以通过命令行使用，本节介绍命令行安装方法。

## 安装

1. 安装`npm`，`npm`是`Node.js`的包管理工具，如何安装`npm`请自行百度。
2. 通过`npm`安装`Gitbook`，命令如下
> npm install gitbook -g

## 使用

#### 目录结构

1. `SUMMARY.md`: `SUMMARY.md`文件里面包含了章节目录结构，可以在这个文件内设置目录。内容格式如下。

```
*  [第1章](c1.md)  
  *  [第1节](c1s1.md)  
  *  [第2节](c1s2.md)  
*  [第2章](c2.md)
```
2. `README.md`: `README.md`文件一般作为电子书概述章节。

#### 预览
通过命令可以实现电子书预览，命令如下，`Gitbook`会生成预览地址，在浏览器中输入地址即可预览，一般预览地址为`http://localhost:4000`。
> gitbook serve -p 8080
