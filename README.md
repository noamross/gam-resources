# Resources for Learning About and Using GAMs in R

In no particular order:

-  [Generalized Additive Models in R: A Free Interactive Course](https://noamross.github.io/gams-in-r-course/), by me. A friendly introduction requiring only basic knowledge of R and linear regression.  4-5 hours of slides and interactive exercises.  This was formerly on a commercial platform but is now open source.
-  [Slides from my talk at the New York R User's Group](2017-11-14-noamross-gams-nyhackr.pdf) (this repo).  This is a high-level overview of things that GAMs and mgcv can do.  Video (~80 minutes) here: <https://www.youtube.com/watch?v=q4_t8jXcQgc>
-  Materials from our [2017 Ecological Society of America workshop on GAMs](https://noamross.github.io/mgcv-esa-workshop/).  These are designed for the interactive workshop but may still be useful.  Target audience is graduate students with a little more statistical training. GLM knowledge a prerequisite. More material on inference, theory and more exotic distributions. See the [references page](https://noamross.github.io/mgcv-esa-2018/links_and_bibliography.html) in particular
    -   The [2018 materials](https://noamross.github.io/mgcv-esa-2018/) are almost exactly the same, but we are tracking issues in that repo for future improvement!
-  The essential GAMs reference is Simon Wood's [Generalized Additive Models in R](https://www.crcpress.com/Generalized-Additive-Models-An-Introduction-with-R-Second-Edition/Wood/p/book/9781498728331).  
    -  Recently reviewed by Virgilio Gomez-Rubio in the [Journal of Statistical Software](https://www.jstatsoft.org/article/view/v086b01)
-  [An online book](https://m-clark.github.io/generalized-additive-models/) by Michael Clark gives an a very nice short introduction to both GAM theory and use in R.
-  Gavin Simpsons's excellent, [GAM-centric blog](https://www.fromthebottomoftheheap.net/) where he tries out new and little-used GAM formulations.
-  [StackOverflow](https://stackoverflow.com/questions/tagged/mgcv) and [Cross Validated](https://stats.stackexchange.com/questions/tagged/mgcv) tags for `mgcv`
    -  Home to Gavin's amazing [Cross Validated answer on spatiotemporal modelling with GAMs](https://stats.stackexchange.com/questions/244042/trend-in-irregular-time-series-data/306361#306361)
-  [A post by Kim Larsen's GAMs on the Stitchfix Blog](http://multithreaded.stitchfix.com/blog/2015/07/30/gam/) which explains GAMs and compares them to other methods for classification.
-  The [**gratia**](https://github.com/gavinsimpson/gratia) package by Gavin Simpson for using **mgcv** with **ggplot2** and other useful and tidy helper functions, such as calculating spline derivatives and simulating from model posteriors.  Here's a [blog post](https://www.fromthebottomoftheheap.net/2018/10/23/introducing-gratia/) introducing it.
-  [Hierarchical Generalized Additive Models: an introduction with mgcv](https://peerj.com/articles/6876/) A paper by Eric J. Pedersen, David L. Miller, Gavin Simpson, and Noam Ross on fitting gams with heirarchical/mixed structures.  [GitHub repo here](https://github.com/noamross/mixed-effect-gams).
-  [Modelling palaeoecological time series using generalized additive models](https://www.biorxiv.org/content/early/2018/05/15/322248), a paper by Gavin L. Simpson
- [Bayesian views of generalized additive modelling](https://arxiv.org/abs/1902.01330), a brief but useful write-up on Bayesian approaches and interpretations of GAMs by Dave Miller.
- [Generalised additive mixed models for dynamic analysis in linguistics: a practical introduction](https://arxiv.org/abs/1703.05339) by [Márton Sóskuthy](https://twitter.com/msoskuthy)
- [Simplified Integrated Nested Laplace Approximation](https://people.maths.bris.ac.uk/~sw15190/ginlane.pdf) by Simon N. Wood, details the `ginla()` function added in **mgcv** 1.8-27.
