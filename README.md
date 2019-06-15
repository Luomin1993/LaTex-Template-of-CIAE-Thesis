# 请使用中国原子能科学研究院学位论文Latex模板

[![Travis Building](https://travis-ci.org/ustctug/ustcthesis.svg?branch=master)](https://travis-ci.org/ustctug/ustcthesis)
[![GitHub release](https://img.shields.io/github/release/ustctug/ustcthesis.svg)](https://github.com/ustctug/ustcthesis/releases/latest)
[![Github All Releases](https://img.shields.io/github/downloads/ustctug/ustcthesis/total.svg)](https://github.com/ustctug/ustcthesis/releases)
[![GitHub commits](https://img.shields.io/github/commits-since/ustctug/ustcthesis/v2.2.3.svg)](https://github.com/ustctug/ustcthesis/commits/master)


--------------------------------------------------------------
>本院论文采用较为老旧的word模板排版,在目录自动生成、引用、数学公式以及修改的灵活性、解耦合等等方面都有太多问题.word工具设计的初衷是给不擅长Tex工具的文科生、艺术生上手排版,作为理工科学生还是应该使用Tex或者LaTex上手排版.本模板修改自中国科学院大学学位论文LaTex模板.

---------------------------------------------------------------
### 前言
事实上中科院各个所(软件所、计算所、高能所...)的研究生学位论文都使用的是这套模板的变种,因此制作满足401的研究生学位论文时我选择在这套模板上修改,使用LaTex排版毕业论文的优点有:

- 可**在线编译**,无须本地设置环境,云存储更方便;
- 排版**数学公式**是 LaTeX 闻名的强项,配合MathPix简直逆天;
- **参考文献**的管理:年轻人一般喜欢用Jabref,但是老夫还是比较喜欢原生的BibTex.
- **自动排版**:所有目录、编号、引用、文本位置均为自动生成.
- **丰富的宏包**:有许多优质的开源宏包在CTAN上可供使用.

-------------------------------------------------------------
### 模板简介
本项目是中国科学技术大学的学位论文 LaTeX 模板,按照<<**中国原子能科学研究院研究生学位论文的编写指南**>>和2019年**答辩材料袋封面排版说明**要求制作,兼容最新版的 TeX Live、MacTeX 、MikTeX 发行版,支持跨平台使用.

><<中国原子能科学研究院研究生学位论文的编写指南>>:
>http://www.ciae.ac.cn/yjs/index_811.htm

>中国科学院大学学位论文 LaTeX 模板:
>https://github.com/xiaoyao9933/UCASthesis

模板的文件组成:

|文件名| 功能 | 
|--|--|
| ustcthesis.dtx | 模板原始代码文件,一般用户无需使用 |
| ustcthesis.cls | 文档类文件 |
| ustcextra.sty | 模板的附加宏包 |
| figures/ciae_logo.png | 院徽图片 |
|main.tex | 主文档|
|chapters/*.tex | 论文的各个章节|
|figures/*.pdf | 放置论文位图/矢量图的目录|
|bib/ref.bib | BibTEX引用文献|

