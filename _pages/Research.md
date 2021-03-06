---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
redirect_from:
  - /Research
---
{% include base_path %}

My current research is mainly focused on information diffusion in social network. 
Previously I worked on developing topic-based methods for academic search and recommendation and visualzation of topic evolution, which are the theoretical part of our [Academic Search Engine](http://acemap.sjtu.edu.cn).

I am also interested in other machine learning related topics (eg. deep learning), data mining, espically graph mining and text mining. 

Ranking papers for different topics in Citation Network.
============
Discovering important papers in different academic topics is known as topic-sensitive influential paper discovery. Previous works mainly find the influential papers based on the structure of citation networks but neglect the text information, while the text of documents gives a more precise description of topics. We conbined textual information to rank the papers and indentify the most important ones among them.

We have made such contributions:
* We conduct empirical observations on real-world dataset to summerize the factors that influence papers to cite.
* We propose a new, robust model to generate the citation network with topic and the importance of papers
* We achieve an improvement on the task of citation prediction and implement our model in academic recommendation.

Paper: X. Huang, C. Chen, C. Peng, X. Wu, L. Fu and X. Wang, "Topic-sensitive Influential Paper Discovery in Citation Network", PAKDD 2018, Melbourne, Australia. [pdf](http://www.cs.sjtu.edu.cn/~fu-ly/paper/Topic-sensitive%20Influential%20Paper%20Dis.pdf)

Topic Evolution in Scholarly Big-data
============
I worked to construct a probablistic graphical model to capture the temporal evolution of topics in scientific publications.

We have made such contributions:
* We provide a topic modelling based model to capture the timestamps and contents of topics.
* We visualised the evolution map of topic with gephi
* Our model can also be applied to information retrival of academic papers.
<table>
          	<tbody>
          		<tr>
          			<td>
                  <img src="/images/evo_p1.png" style="display:block; margin-left:15px; width:80%">
          			</td>
          			<td style="width:340px">
          			<img src="/images/model.png" style="display:block; margin-left:15px; width:80%">
          			</td>
          		</tr>
          	</tbody>
          </table>


An Interactive Topic Model for academic recommendation
============
I worked to construct a topic-based model to recommend scientific publications.
We have made such contributions:
* We provide an interactive topic model with tree-structured priors and encode user feedback into the prior tree.
* We significantly increase the computational efficiency by adopting similar mechanism like SparseLDA. 
* We propose a crowdsourcing framework for recommending publications and further modify our interactive topic model     to a collaborative version. In this scenario, users with similar interests can fix a shared prior tree, which promotes article recommendation in related topics.
<table>
          	<tbody>
          		<tr>
          			<td>
                  <img src="/images/itm2.png" style="display:block; margin-left:15px; width:80%">
          			</td>
          			<td style="width:340px">
          			<img src="/images/itm1.png" style="display:block; margin-left:15px; width:80%">
          			</td>
          		</tr>
          	</tbody>
          </table>


