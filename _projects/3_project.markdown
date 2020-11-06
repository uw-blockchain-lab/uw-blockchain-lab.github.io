---
layout: page
title: don't stop pretraining
description: Get more out of pretrained LMs by continuing to pretrain
img: /assets/img/domains.png
importance: 3
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/domains.png' | relative_url }}" alt="" title="domains"/>
    </div>
</div>
<div class="caption">
    An illustration of data distributions. Task data is comprised of an observable task distribution, usually non-randomly sampled from a wider distribution (light grey ellipsis) within an even larger target domain, which is not necessarily one of the domains included in the original LM pretraining domain – though overlap is possible. We explore the benefits of continued pretraining on data from the task distribution and the domain distribution.
</div>


Cite our paper:
```bib
@@inproceedings{Gururangan2020DontSP,
  title={Don't Stop Pretraining: Adapt Language Models to Domains and Tasks},
  author={Suchin Gururangan and Ana Marasovi{\'c} and Swabha Swayamdipta and Kyle Lo and Iz Beltagy and Doug Downey and Noah A. Smith},
  booktitle={ACL},
  year={2020}
}
```
