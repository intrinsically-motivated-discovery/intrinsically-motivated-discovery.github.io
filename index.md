---
layout: default
---
* * *
## Abstract

Exploration is a corner stone of machine learning algorithms used to discover novel strategies or patterns. 
Intrinsically motivated goal exploration processes (IMGEPs) were shown to enable autonomous agents to efficiently explore and map the diversity of the effects they can produce on their environment.
With IMGEPs, agents self-define their own experiments by imagining goals, then try to achieve them by leveraging their past discoveries. Progressively they learn which goals are achievable and which are not. 
IMGEPs were shown to enable efficient discovery and learning of diverse repertoires of skills in high-dimensional robots.
In this article, we show that the IMGEP framework can also be used in an entirely different application area: automated discovery of self-organized patterns in complex morphogenetic systems. 
We also introduce a new IMGEP algorithm where goal representations are learned online and incrementally (past approaches used precollected training data with batch learning). 
For experimentation, we use Lenia, a continuous game-of-life cellular automaton. 
We study how IMGEPs algorithms enable to discover a variety of complex self-organized visual patterns. 
We compare random search and goal exploration methods with hand-defined, pretrained and online learned goal spaces. 
The results show that goal exploration methods identify more diverse patterns compared to random exploration. 
Moreover, the online learned goal spaces allow to successfully discover interesting patterns similar to the ones manually identified by human experts. 
Our results exemplify the ability of IMGEPs to aid the discovery of novel structures and patterns in complex systems. We are optimistic that their application will aid the understanding and discovery of new knowledge in various domains of science and engineering.

* * *
##  Intrinsically Motivated Goal Exploration Processes (IMGEP)
![IMGEP](https://raw.githubusercontent.com/intrinsically-motivated-discovery/intrinsically-motivated-discovery.github.io/master/assets/media/image/png/imgep_overview.png)


* * *
## Studied system: a continuous cellular automaton (Lenia)
Lenia [[arXiv]](https://arxiv.org/abs/1812.05433) is a continuous cellular automaton similar to Conway's Game of Life.

<iframe width="720" height="405" src="https://www.youtube.com/embed/iE46jKYcI4Y" frameborder="0" allowfullscreen></iframe>
<br>
<br>
<a href="https://chakazul.github.io/Lenia/JavaScript/Lenia.html"> 
Explore the program in javascript: <small>https://chakazul.github.io/Lenia/JavaScript/Lenia.html</small> ![lenia javascript program link](https://raw.githubusercontent.com/Chakazul/Lenia/master/Screencap/JavaScript.png) </a>

* * *
## Learning of Goal Spaces via Online Representation Learning

* * *
## Discoveries

### Diversity of explored patterns


|Diversity in Parameter Space                                  | Diversity in Statistic Space                                  |
|![](./assets/media/image/png/diversity_runparamspace_all.png) | ![](https://raw.githubusercontent.com/intrinsically-motivated-discovery/intrinsically-motivated-discovery.github.io/master/assets/media/assets/media/image/png/diversity_statisticspace_all.png)|

| Statistic Space Diversity for Animals                             |  Statistic Space Diversity for Non-Animals                        |
|![](./assets/media/image/png/diversity_statisticspace_animals.png) | ![](https://raw.githubusercontent.com/intrinsically-motivated-discovery/intrinsically-motivated-discovery.github.io/master/assets/media/image/png/diversity_statisticspace_animals.png)|



### Example of discovered patterns
![](https://raw.githubusercontent.com/intrinsically-motivated-discovery/intrinsically-motivated-discovery.github.io/master/assets/media/image/png/imgep_hgs_discoveries.png)
![](https://raw.githubusercontent.com/intrinsically-motivated-discovery/intrinsically-motivated-discovery.github.io/master/assets/media/image/png/imgep_ogl_discoveries.png)

### Visualisation of the learned goal spaces
Visualisation of the learned goal spaces with the IMGEP-OGL and IMGEP-HGS variants

<iframe width="720" height="405" src="https://www.youtube.com/embed/mpvDazf1lPo" frameborder="0" allowfullscreen></iframe>

* * *
## Aknowledgments
We would like to thank Bert Chan for the valuable discussions and for providing the source code of the Lenia System. 

