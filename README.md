# Unofficial Beamer style of Lingnan (University) College

This is an **unofficial** beamer style of Lingnan (University) College in Sun Yat-sen University.

Style picks red and grey as the main color in pallete, hoping to present the 'Red-Grey Spirit' of lingnan.

Logo image comes from the official site of Lingnan  (University)  College.



## Pattern and Feature

See the `demo.pdf` for details.



## Usage

Copy all  `.sty` files to the same directory of the target `.tex` file which you are about to compile, including:

- beamercolorthemelingnan.sty
- beamerinnerthemelingnan.sty
- beamerouterthemelingnan.sty
- beamerthemelingnan.sty

Add one line to the preamble part of your target `.tex` file as below

```latex
\usetheme{lingnan}
```

And you are done! Just begin your compilation.



For now, this syle has been tested under mactex, texlive and xelatex enviornment.

This style uses biblatex for bibliography, which uses biber as its default backend, so the compile chain should be **xelatex->biber->xelatex->xelatex**.

**Attention**: If you want to try compiling `demo.tex`, you may need to change the Chinese font setting (CJK) in the demo, according to your system and fontset.



## Reference

**Official**:

- [Beamer User Guide](https://mirror.bjtu.edu.cn/CTAN/macros/latex/contrib/beamer/doc/beameruserguide.pdf)
- [Beamer Repository](https://github.com/josephwright/beamer)
- [Overleaf Documentation](https://www.overleaf.com/learn)
- [Biblatex gb7714-2015](https://ctan.math.illinois.edu/macros/latex/contrib/biblatex-contrib/biblatex-gb7714-2015/biblatex-gb7714-2015.pdf)

**Unofficial**:

- [BEAMER appearance cheat sheet](http://www.cpt.univ-mrs.fr/~masson/latex/Beamer-appearance-cheat-sheet.pdf)
- [Beamer Theme Gallery](https://deic-web.uab.cat/~iblanes/beamer_gallery/index.html)
- [Beamer Theme Matrix](https://hartwork.org/beamer-theme-matrix/)
- [Tex Stack Exchange](https://tex.stackexchange.com/)
- [Sun Yat-sen University LaTeX thesis style(unofficial)](https://github.com/sysu/thesis)

- Slides of the International Economics course, lectured by Prof.xiaodong, Lu (Thanks to bokai, zhu)
- Zhihu@段丞博  [Bemaer Style Design](https://zhuanlan.zhihu.com/p/134242281) series articles



Special thanks to the comments and advice from my classmates:

- hanliang, Liu[@HarryLiangDangDang](https://github.com/HarryLiangDangDang);
- bokai, Zhu
- yuming, OuYang.



## Contribution

Any issue or PR are welcome.