---
author: angusferraro
comments: true
date: 2012-08-30 12:29:00+00:00
layout: post
slug: paper-review-tuning-the-climate-of-a-global-model
title: 'Paper review: ''Tuning the climate of a global model'''
wordpress_id: 4
categories:
- science review
tags:
- modelling
- papers
---

**Citation: **Mauritsen, T., et al. (2012),
  [Tuning the climate of a global model](http://www.agu.org/pubs/crossref/2012/2012MS000154.shtml),
  _J. Adv. Model. Earth Syst._, 4, M00A01, doi:10.1029/2012MS000154.


The other day I read a really excellent paper in the open-access model
development journal JAMES (Journal of Advances in Modeling Earth
Systems).

The unique aspect of this paper is its frankness. In it the authors
speak in a clear and honest way about how they tuned the new model
from the Max Planck Institute,
[MPI-ESM](http://www.mpimet.mpg.de/en/wissenschaft/modelle/mpi-esm.html). They
discuss the goals of tuning and the methods used to accomplish
this. Previously model development, seen as an unglamourous subject,
has not been deemed worthy of publications. Although they write from
the point of view of MPI-ESM, the concepts are relevant to all models.


<blockquote>_Evaluating models based on their ability to represent the
TOA [top of the atmosphere] radiation balance usually reflects how
closely the models were tuned to that particular target, rather than
the models' intrinsic qualities._</blockquote>




<blockquote>_...[W]e both document and reflect on the model tuning
that accompanied the preparation of a new version of our model
system...Through the course of preparation we took note of the
decision-making process applied in selecting and adjusting parameters,
and these notes are elaborated upon..._</blockquote>


The language here is remarkably self-aware. Previous generations of
climate models were relatively poorly documented and contained plenty
of mysteries, even to those who developed them. It is unlikely
comphrensive notes on the _decision-making process _(not just the
outcome) were recorded in the development of the CMIP3
models. Developers of the CMIP5 models are required to publish more
details of their model formulation. This is a good thing, but his
paper goes beyond that. It gives us an insight into the actual process
by which the model was developed, not just the end result.

In this paper the authors go on to alter parameters to produce three
alternative 'worlds'. Whereas a perturbed-physics ensemble
systematically varies all parameters within preset bounds and runs
with a huge number of combinations, here the focus is on finding an
equally-valid tuned set of parameters. The model developers recognise
that some choices in the tuning process are somewhat subjective and
that other equally-defensible choices could be made. They then look at
the differences between the 'official' MPI-ESM and the three
alternative 'worlds'. They find some intriguing differences in the way
the models represent smaller-scale features like the land/ocean
contrast in tropical rainfall; usually such improvements weaken other
aspects of the model's climate, introducing an interesting trade-off.

Another interesting point is the extent to which models' ability to
reproduce the 20th Century temperature record is the result of
tuning. The authors squash this idea:


<blockquote>_The MPI-ESM was not tuned to better fit the 20th
Century. In fact, we only had the capability to run the full 20th
Century simulation...after...the model was frozen._</blockquote>


Thus the tuning was based more on physical metrics like the radiation
balance at the top of the atmosphere, cloud and water vapour
amounts. The emphasis was to produce a model which fits with our
physical understanding rather than simply producing a simulator which
reproduced observed temperatures.

For me, one of the implications of this paper was the importance of
maintaining numerous independent models. As the authors here so
candidly explains, model tuning is a subjective process. Choices are
made to improve the representation of some aspects of the climate
system which may degrade performance in other areas. Which areas are
considered more important depend on the opinions of the modelling
group and their research focus. By having numerous models with
different strengths and weaknesses (partially a result of the choices
made during the tuning process) and considering results from the
models together (this is the goal of the CMIPs) we can hope to remove
any bias introduced by these subjective choice.






![](https://blogger.googleusercontent.com/tracker/3910412483840577027-5975608116359054666?l=angusferraro.blogspot.com)
