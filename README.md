# QMUL-BUPT-Latex-template
This is the latex template for the BBC6521 final project of the joint programme between [BUPT](https://www.bupt.edu.cn/) and [QMUL](https://www.qmul.ac.uk/)


## File Tree



```
QMUL-BUPT-Latex-template
│   README.md
│   QMUL_Thesis.tex // the main tex file   
|   output.pdf // an example output pdf file
│
└───Chapters
│   │   Abstract.tex
│   │   intro.tex
|   |   exp.tex
|   |   .....
|
└───Environment
│   │   Bibliography.bib 
│   │   Environments.tex // Special environments we need to define, such as Definition block
│   |   Packages.idx // Packages we used including xeCJK for chinese
│   |   TitlePage.docx // For Title Page
│   └───TitlePage.pdf
│
└───Pictures // folder for your figures in final report
```

## Warning

与学校的word版本还是有一定上的排版差别

（江来出了问题，我可不负泽，红豆泥，私密马赛！

## Envirnment

Has been successfully compiled in [overleaf](https://www.overleaf.com/) with complier ```XeLatex```


## how to use
 

 ### How to compile it
1. Download the zip of this repo from [this link](https://github.com/RicardoL1u/QMUL-BUPT-Latex-template/archive/refs/heads/main.zip)

2. Upload the zip file to [overleaf](https://www.overleaf.com/) 

> In fact, you can use any latex compile tools as you like, for example [TeXstudio](https://www.texstudio.org/)

3. Change the compiler to ```XeLatex``` , a [guide](https://overleaf.com/learn/how-to/Changing_compiler) about how to change compiler in overleaf

3. Enjoy the Latex :)


 ### How to change the header 
Switch to the ```Packages.tex``` in the ```Environment```  folder to change the header to your project title

### How to modify the title page

0. Since my ability is limited, I recommend the way by inserting a pdf to address the title page issue :(

    > If you got any good ideas, for example, modify the ```TitlePage.tex``` to the format that the international school Academic Affairs Office require, plz drop me a pull request

1. Modify the word file ```TitlePage.docx``` in the ```Environment```  folder 

2. Export the word file to the pdf file ```TitlePage.pdf```

3. Recompile



## FAQ

- **Q: LaTeX怎么这么麻烦？**

    A: 使用LaTeX排版学术材料是极受欢迎的，优秀的国际会议和权威的学术杂志鲜见不接受LaTeX投稿的，相反，它们会主动提供符合自家排版要求的LaTeX模板，学者不需要再根据其要求大费周折。当然，它对新手不如word友好，因为其不具有“所见即所得”的特性。但是，“信息黄埔”的你们，应该对“看代码→写代码→编译→看结果”这一套十分熟悉，熟练后他会让你不再陷于反反复复调整格式的泥淖。

- **Q: 用Word排版有那么不堪么？**

    A: 微软的Word是一个优秀的文字处理软件，用它来书写毕业论文没有问题。然而，我们很多同学对它的使用非常肤浅，你甚至还时常能见到“用敲空格的方式把一个标题居中”的人。如果你不太懂自动生成目录，不太懂项目编号，不太懂文档内链接，不太懂上下标，不太懂Word的公式编辑器，不太会调整段落与缩进，不太会处理表格的边框长度和宽度，不太会设置页眉页脚，不太会分节分页，不太会对不同节设置不同页码格式，不太会用合适的方式排列图文……可以说，**你对Word排版的学习成本也是很高的**，既然可以，不妨尝试一种新的排版方式，在撰写学术论文、求职简历和研究生毕业论文时，这项技能还用得上。

- **Q: 为什么我在TeXworks中编译，到“Require XeLaTeX”处就不动了？**

    A:正如编译提示所言，它需要XeLaTeX。请注意编辑器左上角是否选择“XeLaTeX”，默认状态下是pdfLaTeX。

- **Q: LaTeX语句书写有误，导致编译卡在一半怎么办？**

    A:TeXworks中，本次编译可以通过在下方输入框敲击Enter以忽略错误完成，但有时错误无法忽略会导致本次输出PDF不成功。修正好错误后，到“文件”中选择“删除辅助文件”，然后再重新编译即可。
    
 
- **Q: 引用文献的BibTeX文件可以从哪里获取？**

    A:几乎任何学术文献库都会提供BibTeX格式的引用数据，你可以使用**JabRef**来管理和自动生成你引用文献的BibTeX。但在引用量不大的情况下，直接去学术搜索引擎和数据库（Google Scholar/IEEEXplore/ACM digital library/Springer Link/必应学术/百度学术）或学术组织官网（CVF）去复制也不麻烦。

- **Q: 什么样的图片可以插入？**

    A:主流格式如`.png` `.jpg`都支持，但如果你将图片保存为`.pdf`格式，会取得更快的编译速度。
    
- **Q: 我编译后发现部分引用是问号，怎么办？**

    A:如果是参考文献，确保你已经编译了最新的 `.bib` 文件；如果不是，再用XeLaTeX编译一遍。一种粗放的比喻是，**在这里的“编译”就如同Windows的“重启”一样**，虽然暴力但有用。

## TODO
- the format of appendix page // In fact, there is no so-called 'official format' for the appendix part 
- the format of title page
> Both 2 above issues can be temporarily addressed by directly inserting pdf pages in the final report, a [guide](https://stackoverflow.com/questions/2739159/inserting-a-pdf-file-in-latex) about this 
