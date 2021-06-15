# 岭南（大学）学院非官方 Beamer 模板

中山大学岭南（大学）学院**非官方** Beamer 模板。

以红、灰色作为主色调，希望呈现岭南的红灰精神。

学院 logo 图片来自于学院官网。



## 样式特性

详见 `demo.pdf`



## 使用方法

将本仓库内所有 `.sty` 文件复制到准备进行编译的目标 `.tex` 文件同一路径下，包括

- beamercolorthemelingnan.sty
- beamerinnerthemelingnan.sty
- beamerouterthemelingnan.sty
- beamerthemelingnan.sty

在你的目标 `.tex` 文档的导言 preamble 部分加入下面的一句进行调用

````latex
\usetheme{lingnan}
````

搞定！直接编译即可。



目前在 mactex、texlive 与 xelatex 环境下编译测试通过。

模板内使用 biblatex 管理文献，其后端默认使用 biber，所以整体编译链推荐是 **xelatex->biber->xelatex->xelatex**

**注意**：如果希望尝试编译 `demo.tex`，可能需要根据自身系统字体库修改 demo 文档内的中文字体设定（CJK）。



## 参考

**官方**：

- [Beamer User Guide](https://mirror.bjtu.edu.cn/CTAN/macros/latex/contrib/beamer/doc/beameruserguide.pdf)
- [Beamer Repository](https://github.com/josephwright/beamer)
- [Overleaf Documentation](https://www.overleaf.com/learn)
- [Biblatex gb7714-2015](https://ctan.math.illinois.edu/macros/latex/contrib/biblatex-contrib/biblatex-gb7714-2015/biblatex-gb7714-2015.pdf)

**非官方**：

- [BEAMER appearance cheat sheet](http://www.cpt.univ-mrs.fr/~masson/latex/Beamer-appearance-cheat-sheet.pdf)
- [Beamer Theme Gallery](https://deic-web.uab.cat/~iblanes/beamer_gallery/index.html)
- [Beamer Theme Matrix](https://hartwork.org/beamer-theme-matrix/)
- [Tex Stack Exchange](https://tex.stackexchange.com/)
- [中山大学LaTeX论文项目模板(非官方)](https://github.com/sysu/thesis)

- 岭南学院经济系鲁晓东教授在国际经济学课程上所使用的 Slide（感谢 bokai, zhu 友情提供）
- 知乎@段丞博的 [Bemaer 模板设计](https://zhuanlan.zhihu.com/p/134242281) 系列文章



特别感谢我的同学提出的意见和建议，他们是:

- hanliang, Liu[@HarryLiangDangDang](https://github.com/HarryLiangDangDang)
- bokai, Zhu
- yuming, OuYang 



## 贡献

欢迎各种 issue, PR。