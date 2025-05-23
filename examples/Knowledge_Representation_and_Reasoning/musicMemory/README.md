# Music Memory and stylistic composition

This repository contains code from our paper:
- [**Temporal-Sequential Learning With a Brain-Inspired Spiking Neural Network and Its Application to Musical Memory**](https://www.cell.com/patterns/fulltext/S2666-3899(22)00119-2) published in Frontiers in Computational Neuroscience. **https://www.cell.com/patterns/fulltext/S2666-3899(22)00119-2**,
- [**Stylistic composition of melodies based on a brain-inspired spiking neural network**](https://www.frontiersin.org/articles/10.3389/fnsys.2021.639484/full) published in  Frontiers in Systems Neuroscience **https://www.frontiersin.org/articles/10.3389/fnsys.2021.639484/full**.
- [**Mode-conditioned music learning and composition: a spiking neural network inspired by neuroscience and psychology**](https://arxiv.org/pdf/2411.14773) preprint in arXiv **https://arxiv.org/pdf/2411.14773**.

## Requirments

* numpy
* scipy
* pytorch >= 1.7.0
* pretty_midi >= 0.2.9
* music21


## Data preparation

The dataset used here can be referred to the website http://www.piano-midi.de/.
The dataset used in mode-conditioned music learning can be referred to the website https://github.com/lqnankai/Music-Dataset. 


## Run
* Run the script *task/musicMemory.py* to memorize and recall the musical melodies, the result will be recorded in a midi file.
* Run the script *task/musicGeneration.py* to learn and generate melodies with different styles, the result will be recorded in a midi file.
* Run the script *task/mode-conditioned learning.py* to learn and generate melodies with different mode and keys, the result will be recorded in a midi file.
The API and details can be found in these scripts. 

## Citation
If you find this package helpful, please consider citing the following papers:

```BibTex
@article{LQ2020,
    author  = {Liang, Qian and Zeng, Yi and Xu, Bo},
    year    = {2020},
    month   = {07},
    pages   = {51},
    title   = {Temporal-Sequential Learning With a Brain-Inspired Spiking Neural Network and Its Application to Musical Memory},
    volume  = {14},
    journal = {Frontiers in Computational Neuroscience}
}


@article{LQ2021,
    title     = {Stylistic composition of melodies based on a brain-inspired spiking neural network},
    author    = {Liang, Qian and Zeng, Yi},
    journal   = {Frontiers in systems neuroscience},
    volume    = {15},
    pages     = {21},
    year      = {2021},
    publisher = {Frontiers}
}

@misc{liang2024modeconditionedmusiclearningcomposition,
      title={Mode-conditioned music learning and composition: a spiking neural network inspired by neuroscience and psychology}, 
      author={Qian Liang and Yi Zeng and Menghaoran Tang},
      year={2024},
      eprint={2411.14773},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2411.14773}, 
}

```
