---
layout: post
date: 2024-05-10 07:59:00-0400
title: New article on arXiv; "Identifying stable communities in Hi-C using multifractal network modularity"
inline: false
related_posts: false
---



## Identifying stable communities in Hi-C using multifractal network modularity


Lucas Hedström, Antón Carcedo Martínez, and Ludvig Lizana, 

[arXiv:2405.05425](https://arxiv.org/abs/2405.05425)

Chromosome capture techniques like Hi-C have expanded our understanding of mammalian genome 3D architecture and how it influences gene activity. To analyze Hi-C data sets, researchers increasingly treat them as DNA-contact networks and use standard community detection techniques to identify mesoscale 3D communities. However, there are considerable challenges in finding significant communities because the Hi-C networks have cross-scale interactions and are almost fully connected.  This paper presents a pipeline to distill 3D communities that remain intact under experimental noise. To this end, we bootstrap an ensemble of Hi-C datasets representing noisy data and extract 3D communities that we compare with the unperturbed dataset. Notably, we extract the communities by maximizing local modularity (using the Generalized Louvain method), which considers the multifractal spectrum recently discovered in Hi-C maps. Our pipeline finds that stable communities (under noise) typically have above-average internal contact frequencies and tend to be enriched in active chromatin marks. We also find they fold into more nested cross-scale hierarchies than less stable ones. Apart from presenting how to systematically extract robust communities in Hi-C data, our paper offers new ways to generate null models that take advantage of the network's multifractal properties. We anticipate this has a broad applicability to several network applications.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/stable-com-infographics.jpg" title="infographics" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Alluvial diagram illustrating how the node stability in the Hi-C networks changes between different chromosome scales. Most flow lines connect the same stability category (red to blue colors) or one nearby. This indicates that stability is a conserved property through the chromosomes' folding hierarchies (e.g., bottom, dark red). The bar charts on the left and right show the enrichment of the chromatin state. The three leftmost bars represent chromatin associated with active genomic regions (defined by histone modifications and DNA-binding proteins). This alluval argues that similar mechanisms drive the cross-scale folding on select parts of the chromosome.
</div>


{% raw %}

```
@article{hedstrom2024identifying,
	title={Identifying stable communities in Hi-C using multifractal network modularity},
  	author={Lucas Hedstr\"om and Ant\'on Carcedo Mart\'inez and Ludvig Lizana},
  	journal={arXiv:2405.05425},
  	year={2024},
}
```

{% endraw %}