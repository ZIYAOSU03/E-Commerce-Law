# 电子商务法课程论文（LaTeX 工程）

## 主题
**题目：从“亮照亮证”到“信息可得”——论电子商务经营者的信息公示义务及其实现路径**

## 文件结构
- `main.tex`：主文件（封面、目录、章节引用、参考文献）
- `chapters/`：分章内容
- `references.bib`：参考文献（GB/T 7714-2015）

## 编译（XeLaTeX + BibTeX）
在本目录下执行：

```bash
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```


