# Nielsen-Chuang-Solutions
A repository of hints and solutions for Michael Nielsen and isaac Chuang's Book, Quantum Computation and Quantum Information, 10th Anniversary Edition.  

See the solutions pdf [here](https://github.com/MonitSharma/Nielsen-Chuang-Solutions/blob/master/Nielson_and_Chuang_Solutions%20updated%20%4022012023.pdf)

This is a crowdsourced repository of solutions and hints.  
Any student of Quantum Computation and information knows that this book has played a significant role in their learning process, and solving the exercises was an integral part of this process. Though many problems were extremely difficult at first sight and needed help or coming back to it at a later point of time. Till date according to our knowledge, there is no complete typed out solutions for the same, with useful hints. So we believe this repository could be quite useful for new learners in their journey.  

Anyone is free to contribute to this. Please follow the below guidelines.
## Contributing Guidelines:  
(last updated on 23rd July 2020)  
1) Add your names against the Exercise/problem who's hints and solutions you wish to contribute to: [list of contributors](https://docs.google.com/spreadsheets/d/1zf0NDke0a6qjcPdUnzLeqmgeyLlFFOKjl5Vcq9p2Ltw/edit?usp=sharing)  
2) Filename of the form: yourname_insert_random_number.tex (to avoid clashes of any form).  
3) Each time you pick problems or a set of problems, either commit directly to master or make a pull request with the .tex files and the corresponding images only, make sure the files are created in the respective folders chapterwise. Once we have most solutions to the chapter, one of us will review and compile together.  
4) If you know you are overwriting an existing file, make a pull request only.  
5) Avoid profanity of any kind and be nice to each other :)  

The LaTeX ecosystem is known for redundant packages. To ensure that we can can compile the contributed `.tex` files, we suggest that you follow the following guidelines.
### LaTeX Guidelines:  
(last updated on 23rd July 2020)
1) Use the default `article` class, and the default font.
2) Feel free to use the AMS-LaTeX collection. For multiline equations, please use the `align` environment.
3) For the Dirac notation use the `braket` package. (Details are [here](https://ctan.org/tex-archive/macros/latex/contrib/braket?lang=en).)
4) If you want to draw circuit diagrams, use the `tikz` and `quantikz` packages. (Details are [here](https://ctan.org/pkg/quantikz?lang=en).)
5) If you have to absolutely use any additional / non-standard packages, then please mention that in you commit message.
