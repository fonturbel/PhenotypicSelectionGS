# Tristerix phenotypic selection :sunglasses:

This repository contains data and code related to a new approach on phenotypic selection gradient analysis for plants (using the hemiparasitic mistletoe _Tristerix corymbosus_ as a model), incorporating spatial and genetic data into classic Lande & Arnold equations. Here we developed new models and tested other approaches that were little useful.

## The models proposed :nerd_face:
Here we compare the performance of:

(i) the classic model
(ii) a model incorporating spatial structure
(iii) a model incorporating the genetic structure, accounting for inter-individual relatedness
(iv) a model incoporating both spatial and genetic terms.

These models constitute a (sort of) novel approach that could be applied to any wild plant population.

## The study model :leaves:
To test our models we are using an existing dataset on  _Tristerix corymbosus_ that was previously used to estimate phenotypic selection on three friuit traits (i.e., fruit size, seed size, and sugar content). Those results can be found in [this paper](https://www.nature.com/articles/srep45371) and the dataset is freely available at the [figshare repository](http://dx.doi.org/10.6084/m9.figshare.4614769).

![Tristerix corymbosus](/images/tristerix.jpg)

We also used genetic information (microsatellite markers) of the same _T. corymbosus_ plants from [another paper](https://doi.org/10.1016/j.scitotenv.2018.10.125). Our [dataset](https://doi.org/10.6084/m9.figshare.4728721) contains ten microsatellite markers that can be used to estimate inter-individual relatedness.

## IMPORTANT: Contribution rules

Before changing or adding code, please keep these recommendations in mind:

- Use English for code, data, and metadata. Avoid writting stuff in Spanish, this will spare us to spend a lot of time translating the text.
- Keep variable and file names informative and R-friendly (no spaces, accentuated characters, etc.)
- Be as thorough as possible when describing metadata. Imagine yourself trying to understand your own code after one year :sweat_smile:

## Publication

This manuscript has been sent to Evolutionary Ecology on June 22th 2020.