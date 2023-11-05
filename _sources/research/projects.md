# Selected projects

## Hierarchical Dirichlet Process Hidden Markov Trees

Joint work with <a href="http://www.ics.uci.edu/~sudderth/">Erik B. Sudderth</a> and <a href="http://www.cs.berkeley.edu/~jordan/">Michael I. Jordan</a>.  

```{figure} hdp-hmt_figure.png
---
height: 320px
name: fig:hdp-hmt_figure
---
```

We developed a nonparametric Bayesian modeling framework in which data is generated via tree-structured probabilistic graphical models with latent variables, 
whose complexity is determined in a data-driven and -adaptive way. Tree-structured graphical models have natural ties, for example to multiscale data. 
The hierarchical Dirichlet process hidden Markov tree (HDP-HMT) framework extended prior work on, e.g., hidden Markov trees {cite}`crouse98`, 
providing a principled and practical approach to determine the amounts of latent states, automatically via the use of hierarchical Dirichlet process {cite}`teh06`. 
We developed methodology for effective learning and inference with the framework, and explored applications to computational vision tasks, 
producing state-of-the-art results (at the time). 

### Conference and workshop publications and their related presentation materials

* <a href="documents/kivinen+sudderth+jordan_npbayes08_abstract.pdf">Transfer Denoising with Hierarchical Dirichlet Process Hidden Markov Trees</a><br>
Jyri J. Kivinen, Erik B. Sudderth, and Michael I. Jordan<br>
In Nonparametric Bayes Workshop (<a href="http://npbayes.wikidot.com/">NPBayes 2008</a>) at ICML/UAI/COLT 2008, July 2008, Helsinki, Finland <br>
<a href="documents/kivinen+sudderth+jordan_npbayes08_poster.pdf">Poster</a>, <a href="documents/kivinen+sudderth+jordan_npbayes08_spotlight.pdf">Spotlight</a>

* <a href="https://www.icsi.berkeley.edu/icsi/node/3960">Learning Multiscale Representations of Natural Scenes Using Dirichlet Processes</a><br>
Jyri J. Kivinen, Erik B. Sudderth, and Michael I. Jordan<br>
In Proc., IEEE International Conference on Computer Vision (ICCV), Oct. 2007, Rio de Janeiro, Brazil <br>
<a href="documents/kivinen+sudderth+jordan_iccv07_poster.pdf">Poster</a>

* <a href="https://www.icsi.berkeley.edu/icsi/node/3943">Image Denoising with Nonparametric Hidden Markov Trees</a><br>
Jyri J. Kivinen, Erik B. Sudderth, and Michael I. Jordan<br>
In Proc., IEEE International Conference on Image Processing (ICIP), Sep. 2007, San Antonio, Texas, USA<br>
<a href="documents/kivinen+sudderth+jordan_icip07_slides.pdf">Slides</a>

### Drafts

* <a href="documents/kivinen+sudderth+jordan_hdp-hmt_journal_article_draft.pdf">Hierarhical Dirichlet Process Hidden Markov Trees for Multiscale Image Analysis</a><br>
Jyri J. Kivinen, Erik B. Sudderth, and Michael I. Jordan
 
### Selected other resources

* <a href="documents/kivinen_icsforum09_slides.pdf">Multiscale Image Modeling and Analysis with Hierarchical Dirichlet Process Hidden Markov Trees</a><br>
Jyri J. Kivinen<br>
Invited talk at Information and Computer Science Forum, Helsinki University of Technology, 21 Aug. 2009

* <a href="https://ics.uci.edu/~sudderth/bnpCVPR12/slides/BNP4hdphmt.pdf">Infinite Hidden Markov Trees</a><br>
Erik B. Sudderth<br>
<a href="https://ics.uci.edu/~sudderth/bnpCVPR12/">Applied Bayesian Nonparametrics</a>, Tutorial Course at CVPR 2012, 17 June 2012

### References
```{bibliography}
:filter: docname in docnames
```

