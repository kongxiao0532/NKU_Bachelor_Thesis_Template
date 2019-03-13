# 南开大学本科生毕业论文(毕业设计)LaTeX模板
* 本模板除了标准字体外还用到了“方正粗楷简体”，个人授权免费，需自行下载安装。
* Windows下测试编译通过。
## 已知问题
* 英文题目无法自动换行
## 模板来源
[南开大学研究生（博士生）毕业论文LaTeX模板](https://github.com/NewFuture/NKThesis)

thanks to @darfux， @NewFuture

## 当前标准
[南开大学本科毕业论文（设计）指导手册2018](http://jwc.nankai.edu.cn/_upload/article/files/f6/fc/675d5e094f02aeb702713dc30c8b/08092332-2f1f-42e3-88a6-fefe082e1147.doc),[本科生论文格式要求补充规定2016V1_2_21]

## 编写

### 编译方式
`xelatex`(Tex编译)+`biber`(参考文献编译)

#### 编译脚本

* windows 双击 `build.cmd`即可
* linux 在此目录下运行 `./build.cmd`即可

#### 手动编译:

```
xelatex main
biber main
xelatex main
xelatex main
```

### 推荐编辑器和工具

基本要求: 自动补全，语法高亮，错误提示,实时预览,光标同步


* [sublime](https://www.sublimetext.com/) + [LatexTools插件](https://github.com/SublimeText/LaTeXTools) +[Sumatra pdf](https://www.sumatrapdfreader.org/download-free-pdf-viewer.html)
* [VS code](https://code.visualstudio.com/) + [LaTeX-Workshop插件](https://github.com/James-Yu/LaTeX-Workshop)


## 说明

### 文件
* [main.tex](main.tex)模板入口
* [nkthesis.bib](nkthesis.bib) 参考文献bib文件，可使用Google学术或百度学术直接导出bibtex格式
* [tex/文件夹](tex/) 每一章单独一个文件,主要写作部分

### 其他

* 支持绘图
* 支持语法高亮(`python`和`c++`特别优化)
