# Introduction to Algorithms, Fourth Edition &mdash; solutions to exercises and problems

![Build PDF](https://github.com/wojtask/clrs4e-solutions/actions/workflows/build.yml/badge.svg)

### Overview

The goal of this project is to provide solutions to all exercises and problems from *Introduction to Algorithms, Fourth
Edition* by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest and Clifford Stein.
My intention is to ensure, first and foremost, the rock solid correctness and completeness of the provided content, its
technical elegance, as well as its consistency with the textbook material.
In order to achieve such reliability, I spend a lot of time evolving and revising the solutions, not only in terms of
content, but also in terms of terminology, wording, and typography.
I pay attention to providing optimal algorithms, which are then implemented and thoroughly tested, and to illustrate
operations and examples with accurate pictures, consistent with the style of the textbook.

It should be noted that the textbook's authors also provide selected solutions &mdash; they can be downloaded from the
[textbook's website](http://mitpress.mit.edu/algorithms4).
Also, other authors publicly host their solutions on the web, though majority of those that I found are for the third
edition of the textbook:

* [solutions by Michelle Bodnar and Andrew Lohr](http://sites.math.rutgers.edu/~ajl213/CLRS/CLRS.html),
* [solutions by Stefan Kanev](https://ita.skanev.com),
* [solutions by Don R. Walsh](https://donrwalsh.github.io/CLRS),
* [crowdsourced solutions coordinated by Peng-Yu Chen](https://walkccc.github.io/CLRS),
* [the textbook's page on Quizlet](https://quizlet.com/explanations/textbook-solutions/introduction-to-algorithms-4th-edition-9780262046305).

However, none of the above sources cover all exercises, especially when compared to the fourth edition that adds
significant number of new exercises.
Also, I noticed that certain solutions are not of the highest quality, e.g., some of them are incorrect, incomplete, or
just far from elegance.
Nevertheless, these pieces of work were sources of inspiration for me, presented different approaches and perspectives.
When relying on the ideas from them, I always aimed to rework the solutions by introducing necessary fixes and
improvements, or just polishing them.

The solutions here often refer to the material presented in the textbook, so familiarity on at least a current chapter
is required.
In many solutions, you will also find references to other tasks, especially when a given task uses the result of another
in its own solution.
In general, later solutions sometimes rely on the earlier ones by referencing the relevant exercises.
Thus, in early chapters one can observe a somewhat greater focus on details, and in later chapters more cross-references
to exercises where those details have already been discussed.

I keep an eye on errors or inaccuracies in exercises and problems or the material they directly rely on, and highlight
them in short notes before the solution of the affected exercise.
On the other hand, I refer to the
textbook's [errata](https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/11599/e4-bugs.html) &mdash;
if it includes a certain correction, I assume that the bug has already been fixed.

As I stressed earlier, I pay special attention to ensuring the correctness of the algorithms and data structures
operations.
To maximize my confidence, I implement and test each pseudocode or algorithm description that I provide in the
solutions, as well as those that are provided in the textbook.
I chose Python as a programming language, because of its popularity and its syntax similar to that used in pseudocodes.
The counterpart project with implementations is available on [here](https://github.com/wojtask/clrs4e-implementations).

[The list of provided algorithms.](ALGORITHMS.md)

[Detailed project's conventions.](CONVENTIONS.md)

### History

The origins of the project date back to 2005, when I started solving exercises by pen and paper, during studying
algorithms as a preparation for participating in the Polish Olympiad in Informatics.
I was relying on the Polish translation of the textbook's second edition, titled *Wprowadzenie do algorytmów*, and my
solutions were in Polish as well.
In 2009 I started rewriting them in LaTeX.
The document has evolved since then, with changes involving numerous fixes, improved page layout and styling, as well as
open sourcing it on GitHub as [**CormenSol**](https://github.com/wojtask/CormenSol).
At the beginning the pictures were drawn in MetaPost, before having been rewritten to PGF/TikZ in 2016.
In 2012 I started implementing algorithms, first in C++, then in Java, before finally settling on Python in 2017, and I
open sourced the implementations as [**CormenPy**](https://github.com/wojtask/CormenPy).
Since initiating the project, the textbook got updated to the third edition in 2009, then to fourth edition in 2022.
Having solved Chapters 1-17 and Appendices A-C from the &mdash; now outdated &mdash; second edition, I decided to freeze
both **CormenSol** and **CormenPy**, and shift my attention to adapt the solutions for the fourth edition, while
translating them to English &mdash; the process I refer to as **migration**.

The work on the current project started on January 1, 2023.

### Progress

| Part I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Part II                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Part III                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Part IV                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Part V                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Part VI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Part VII                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Part VIII                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [![Chapter 1](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/3?color=green)](https://github.com/wojtask/clrs4e-solutions/milestone/3)<br>[![Chapter 2](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/4)](https://github.com/wojtask/clrs4e-solutions/milestone/4)<br>[![Chapter 3](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/5)](https://github.com/wojtask/clrs4e-solutions/milestone/5)<br>[![Chapter 4](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/6)](https://github.com/wojtask/clrs4e-solutions/milestone/6)<br>[![Chapter 5](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/7)](https://github.com/wojtask/clrs4e-solutions/milestone/7) | [![Chapter 6](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/8)](https://github.com/wojtask/clrs4e-solutions/milestone/8)<br>[![Chapter 7](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/9)](https://github.com/wojtask/clrs4e-solutions/milestone/9)<br>[![Chapter 8](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/10)](https://github.com/wojtask/clrs4e-solutions/milestone/10)<br>[![Chapter 9](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/11)](https://github.com/wojtask/clrs4e-solutions/milestone/11) | [![Chapter 10](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/12)](https://github.com/wojtask/clrs4e-solutions/milestone/12)<br>[![Chapter 11](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/13)](https://github.com/wojtask/clrs4e-solutions/milestone/13)<br>[![Chapter 12](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/14)](https://github.com/wojtask/clrs4e-solutions/milestone/14)<br>[![Chapter 13](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/15)](https://github.com/wojtask/clrs4e-solutions/milestone/15) | [![Chapter 14](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/16)](https://github.com/wojtask/clrs4e-solutions/milestone/16)<br>[![Chapter 15](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/17)](https://github.com/wojtask/clrs4e-solutions/milestone/17)<br>[![Chapter 16](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/18)](https://github.com/wojtask/clrs4e-solutions/milestone/18) | [![Chapter 17](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/19)](https://github.com/wojtask/clrs4e-solutions/milestone/19)<br>[![Chapter 18](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/20)](https://github.com/wojtask/clrs4e-solutions/milestone/20)<br>[![Chapter 19](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/21)](https://github.com/wojtask/clrs4e-solutions/milestone/21) | [![Chapter 20](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/22)](https://github.com/wojtask/clrs4e-solutions/milestone/22)<br>[![Chapter 21](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/23)](https://github.com/wojtask/clrs4e-solutions/milestone/23)<br>[![Chapter 22](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/24)](https://github.com/wojtask/clrs4e-solutions/milestone/24)<br>[![Chapter 23](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/25)](https://github.com/wojtask/clrs4e-solutions/milestone/25)<br>[![Chapter 24](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/26)](https://github.com/wojtask/clrs4e-solutions/milestone/26)<br>[![Chapter 25](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/27)](https://github.com/wojtask/clrs4e-solutions/milestone/27) | [![Chapter 26](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/28)](https://github.com/wojtask/clrs4e-solutions/milestone/28)<br>[![Chapter 27](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/29)](https://github.com/wojtask/clrs4e-solutions/milestone/29)<br>[![Chapter 28](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/30)](https://github.com/wojtask/clrs4e-solutions/milestone/30)<br>[![Chapter 29](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/31)](https://github.com/wojtask/clrs4e-solutions/milestone/31)<br>[![Chapter 30](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/32)](https://github.com/wojtask/clrs4e-solutions/milestone/32)<br>[![Chapter 31](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/33)](https://github.com/wojtask/clrs4e-solutions/milestone/33)<br>[![Chapter 32](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/34)](https://github.com/wojtask/clrs4e-solutions/milestone/34)<br>[![Chapter 33](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/35)](https://github.com/wojtask/clrs4e-solutions/milestone/35)<br>[![Chapter 34](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/36)](https://github.com/wojtask/clrs4e-solutions/milestone/36)<br>[![Chapter 35](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/37)](https://github.com/wojtask/clrs4e-solutions/milestone/37) | [![Appendix A](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/38?color=green)](https://github.com/wojtask/clrs4e-solutions/milestone/38)<br>[![Appendix B](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/39?color=green)](https://github.com/wojtask/clrs4e-solutions/milestone/39)<br>[![Appendix C](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/40?color=green)](https://github.com/wojtask/clrs4e-solutions/milestone/40)<br>[![Appendix D](https://img.shields.io/github/milestones/progress-percent/wojtask/clrs4e-solutions/41?color=green)](https://github.com/wojtask/clrs4e-solutions/milestone/41) |

### Roadmap

- [x] Add project's documentation (you are reading it now), create issues and milestones, setup document's stub, suggest
  page layout and styling.
- [x] Migrate the CormenSol solutions from Appendices A-C. Add solutions to the modified and new exercises and problems
  along the way.
- [x] Add solutions to Appendix D, previously missing in the second edition, completing Part VIII ([release 0.1](https://github.com/wojtask/clrs4e-solutions/releases/download/0.1/clrs4e-solutions.pdf)).
- [ ] Migrate the CormenSol solutions from Chapters 1-17 and the corresponding CormenPy implementations.
  Add solutions and implementations to modified and new exercises and problems along the way.
  - [ ] Complete Part I (release 0.2).
  - [ ] Complete Part II (release 0.3).
  - [ ] Complete Part III (release 0.4).
  - [ ] Complete Part IV (release 0.5).
  - [ ] Complete Chapter 17 from Part V.
- [ ] Add solutions and implementations to Chapters 18-35.
  - [ ] Complete Part V (release 0.6).
  - [ ] Complete Part VI (release 0.7).
  - [ ] Complete selected chapters from Part VII (release 0.8).
  - [ ] Complete Part VII (release 0.9).
- [ ] Finalize the document (release 1.0).

### Building

To compile the project locally you need TeXLive 2021 or newer.
On Ubuntu the minimal required set of packages can be installed with:

```shell
sudo apt install texlive texlive-latex-extra latexmk
```

Additionally, you need to install the MathTime Professional II Lite fonts.
Since the fonts are not available in the standard TeXLive distribution, you will need to install them using the provided
setup script:

```shell
chmod +x setup.sh && sudo ./setup.sh
```

Once the environment is prepared, you can compile the document to PDF by running the following command:

```shell
latexmk -pdf -file-line-error -halt-on-error -interaction=nonstopmode clrs4e-solutions.tex
```

### Contributions

Again, significant effort has been made to ensure that each solution is thoroughly checked.
However, if you have found an error of any kind, or you can improve an existing solution in any way, I will be grateful
for your feedback or help.
Each exercise and each subproblem has its own issue in this repository, named and categorized appropriately.
Please avoid duplicating these issues, rather search for the right one, and leave a comment, or even better &mdash; create a pull request with your suggestions.
Authors of significant contributions will be credited in the document.

**Together let's make this the most complete, reliable and consistent set of solutions to the iconic CLRS!**

&mdash; *Krzysztof Wojtas*
