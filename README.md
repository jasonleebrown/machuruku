# machuruku
Machuruku is an R package developed with [Wilson X. Guillory](https://scholar.google.com/citations?user=a_n1uCIAAAAJ&hl=en) for phylogenetic niche modeling.  Machuruku, which named after the Quechua word for 'ancient', estimates ancestral distributions based on ancestral niche reconstructions and niche-modeling. Machuruku uses a modified Bioclim niche-modeling method and ancestral character estimation to reconstruct ancestral niches. Input data consists of present-day climate rasters, a time-calibrated phylogeny, and taxon occurrence data for all tips. Ancestral niche models can be projected into additionally provided paleoclimate data (www.paleoclim.org) to visualize the geographic origins of a lineage.The most update version of this is hosted on Wilson's Github: https://github.com/wxguillo/machuruku.  Please stay tunned for the assocaited paper coming soon in Systematic Biology!

To install Machuruku, simply run the following in R:
```
install.packages("devtools")
devtools::install_github("wxguillo/machuruku")
```
For both quick and detailed tutorials on how to use Machuruku, please visit the [tutorial page](https://github.com/wxguillo/machuruku/tree/main/tutorial) in this repository.


**Software citation and associated manuscript:**
Guillory WG, Brown JL. A new method for integrating ecological niche modeling with phylogenetics to estimate ancestral distributions. Systematic Biology - in press

![Alt text](https://raw.githubusercontent.com/jasonleebrown/machuruku/master/machurukuLogoShamelessFrog.jpg?raw=true "Title")

