# Data Cleansing with Contrastive Learning for Vocal Note Event Annotations

## ABSTRACT

Data cleansing is a well studied strategy for cleaning erroneous labels in datasets, which has not yet been widely adopted in Music Information Retrieval.Previously proposed data cleansing models do not consider structured (e.g. time varying) labels, such as those common to music data.We propose a novel data cleansing model for time-varying, structured labels which exploits the local structure of the labels, and demonstrate its usefulness for vocal note event annotations in music.Our model is trained in a contrastive learning manner by automatically contrasting likely correct labels pairs against local deformations of them.We demonstrate that the accuracy of a transcription model improves greatly when trained using our proposed data cleaning strategy compared with the accuracy when trained using the original dataset.Additionally we use our model to estimate the annotation error rates in the DALI dataset, and highlight other potential uses for this type of model.

## ANNOTATIONS

SOON


## How to use this package:

SOON


You can find a detailed explanation at:
**[Meseguer-Brocal_2020]** [Meseguer-Brocal, Gabriel and Bittner, Rachel and Durand, Simon and Brost, Brian. Data Cleansing with Contrastive Learning for Vocal Note Event Annotations.](https://arxiv.org/abs/2008.02069).

Cite this paper:

>@inproceedings{Meseguer-Brocal_2019,
	Author = {Meseguer-Brocal, Gabriel and Bittner, Rachel and Durand, Simon and Brost, Brian},
	Booktitle = {21th International Society for Music Information Retrieval Conference},
	Editor = {ISMIR},
	Month = {October},
	Title = {Data Cleansing with Contrastive Learning for Vocal Note Event Annotations.},
	Year = {2020}}

### CONTACT

You can contact us at:

  > gabriel dot meseguerbrocal at ircam dot fr
  > rachelbittner at spotify dot com
  > durand at spotify dot com
  > brianbrost at spotify dot com
