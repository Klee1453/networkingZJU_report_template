### 使用方式

#### 修改封面页上的个人信息

只需要修改`main.tex`文档的导言区中，`\newcommand{\courseName}{计算机网络基础}`等宏语句即可

#### 修改文档内容

修改`^sec.*\.tex`，例如`sec1.tex`

如果需要添加更多`.tex`文件，可以在`main.tex`中使用`\input`语句

一些实例被放在了

#### 编译

使用`xelatex`编译`main.tex`

#### 注意

如果你正在使用LaTeXWorkshop，不要删除掉`.tex`文件中的第一行注释👇

```latex
% !TEX root = ./main.tex
```

> To find the root file, LaTeX Workshop will follow the steps below, stopping whenever one is found:
> - Magic comment `% !TEX root = relative/or/absolute/path/to/root/file.tex`. If such comments exist in the currently active editor, the referred file is set as root.
> - ...

### 兼容性

| | |
| :- | :-: |
| Windows平台使用MikTeX发行版 | ✅ |
| Windows平台使用TeXLive发行版 | ✅ |
