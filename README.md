# Nielsen and Chuang Solutions Manual

Welcome to the *Nielsen and Chuang Solution Manual* GitHub repository!




## Introduction


This repository contains solutions to the exercises in the textbook **"[Quantum Computing and Quantum Information,10th Anniversary Edition.](http://mmrc.amss.cas.cn/tlb/201702/W020170224608149940643.pdf)"** by [Michael Nielsen](https://michaelnielsen.org/) and [Isaac Chuang](http://feynman.mit.edu/ike/homepage/index.html). The solutions have been crowdsourced from a community of students and researchers, and are intended to serve as a useful resource for anyone studying the material in the book.


As a fundamental resource in the field of quantum computation and information, "Quantum Computing and Quantum Information" by Michael Nielsen and Isaac Chuang is widely recognized for its role in facilitating the learning process of students in the field. The book's exercises, in particular, have been an integral component of this process, providing opportunities for readers to apply and solidify their understanding of the material. Despite the value of these exercises, however, comprehensive solutions with helpful hints have not been readily available. In light of this, we have established this repository as a resource for students and learners to aid in their understanding of the material by providing solutions to the exercises in the book.





## Solutions


Check the complete solutions here :  [Quantum Computing and Quantum Information,10th Anniversary Edition.](https://github.com/MonitSharma/Nielsen-Chuang-Solutions/blob/master/Nielson_and_Chuang_Solutions%20updated%20%40%2022042023.pdf)

The solutions are organized by chapter and exercise, and are provided in a variety of formats including `PDF` and `LaTeX`. Additionally, there are a few different versions of the solutions, which are organized into different branches of the repository.

The master branch of the repository contains the latest and most up-to-date solutions. We welcome contributions from the community, so if you have a solution to an exercise that is not currently in the repository, please feel free to submit a pull request.

Please note that the solutions provided in this repository are not guaranteed to be correct, and should be used as a guide rather than a definitive answer. If you are using these solutions as a resource, it is important to check your work against the solutions to ensure that you understand the material.

Thank you for using the *"Nielsen and Chuang Solution Manual"* repository, and we hope that it is a valuable resource for your studies.






## Contributing Guidelines:  

(last updated on 24th January 2023)  
1.  Add your names against the Exercise/problem who's hints and solutions you wish to contribute to: [list of contributors](https://docs.google.com/spreadsheets/d/1zf0NDke0a6qjcPdUnzLeqmgeyLlFFOKjl5Vcq9p2Ltw/edit?usp=sharing)  
2.  Filename of the form: `yourname_insert_random_number.tex` (to avoid clashes of any form).  
3.  Each time you pick problems or a set of problems, either commit directly to master or make a pull request with the `.tex` files and the corresponding images only, make sure the files are created in the respective folders chapter-wise. Once we have most solutions to the chapter, one of us will review and compile together.  
4.  If you know you are overwriting an existing file, make a pull request only.  
5.  If you find any error be sure to raise an issue. We'll try to review it asap.
6.  Avoid profanity of any kind and be nice to each other :)  


*Learn how to contribute a PR or raise an issue in the [official Github Docs](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request)*

**Anyone is free to contribute to this. Please follow the below guidelines.**







## LaTeX guidelines

The `LaTeX` ecosystem is known for redundant packages. To ensure that we can can compile the contributed `.tex` files, we suggest that you follow the following guidelines.

(last updated on 24th January 2023)
1. Use the default `article` class, and the default font.
2. Feel free to use the AMS-LaTeX collection. For multiline equations, please use the `align` environment.
3. For the Dirac notation use the `braket` package. (Details are [here](https://ctan.org/tex-archive/macros/latex/contrib/braket?lang=en).)
4. If you want to draw circuit diagrams, use the `tikz` and `quantikz` packages. (Details are [here](https://ctan.org/pkg/quantikz?lang=en).)
5. If you have to absolutely use any additional / non-standard packages, then please mention that in you commit message.
