# Resources for Learning About and Using GAMs in R

In no particular order:

- My [DataCamp course on GAMs](https://www.datacamp.com/courses/nonlinear-modeling-in-r-with-gams).  Aimed at beginners, with basic R and linear regression experience
-  [Slides from my talk at the New York R User's Group](2017-11-14-noamross-gams-nyhackr.pdf) (this repo).  This is a high-level overview of things that GAMs and mgcv can do.  Video (~80 minutes) here: <https://www.youtube.com/watch?v=q4_t8jXcQgc>
-  Materials from our [2017 Ecological Society of America workshop on GAMs](https://noamross.github.io/mgcv-esa-workshop/).  These are designed for the interactive workshop but may still be useful.  Target audience is graduate students with a little more statistical training. GLM knowledge a prerequisite.  See the [references page](https://noamross.github.io/mgcv-esa-2018/links_and_bibliography.html) in particular
    -   The [2018 materials](https://noamross.github.io/mgcv-esa-2018/) are almost exactly the same, but we are tracking issues in that repo for future improvement!
-  The essential GAMs reference is Simon Wood's [Generalized Additive Models in R](https://www.crcpress.com/Generalized-Additive-Models-An-Introduction-with-R-Second-Edition/Wood/p/book/9781498728331).  
    -  Recently reviewed by Virgilio Gomez-Rubio in the [Journal of Statistical Software](https://www.jstatsoft.org/article/view/v086b01)
-  Gavin Simpsons's excellent, [GAM-centric blog](https://www.fromthebottomoftheheap.net/) where he tries out new and little-used GAM formulations.
-  [StackOverflow](https://stackoverflow.com/questions/tagged/mgcv) and [Cross Validated](https://stats.stackexchange.com/questions/tagged/mgcv) tags for `mgcv`
    -  Home to Gavin's amazing [Cross Validated answer on spatiotemporal modelling with GAMs](https://stats.stackexchange.com/questions/244042/trend-in-irregular-time-series-data/306361#306361)
-  [A post by Kim Larsen's GAMs on the Stitchfix Blog](http://multithreaded.stitchfix.com/blog/2015/07/30/gam/) which explains GAMs and compares them to other methods for classification.
-  The [**gratia**](https://github.com/gavinsimpson/gratia) package by Gavin Simpson for using **mgcv** with **ggplot2** and other useful and tidy helper functions.  Here's a [blog post](https://www.fromthebottomoftheheap.net/2018/10/23/introducing-gratia/) introducing it.
-  [Hierarchical Generalized Additive Models: an introduction with mgcv](https://peerj.com/preprints/27320/) A paper by Eric J. Pedersen, David L. Miller, Gavin Simpson, and Noam Ross on fitting gams with heirarchical/mixed structures.  [GitHub repo here](https://github.com/noamross/mixed-effect-gams).
-  [Modelling palaeoecological time series using generalized additive models](https://www.biorxiv.org/content/early/2018/05/15/322248), a paper by Gavin L. Simpson
- (Bayesian views of generalized additive modelling)[https://arxiv.org/abs/1902.01330], a brief but useful write-up on Bayesian approaches and interpretations of GAMs.
