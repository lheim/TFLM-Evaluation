# Measuring what Really Matters: Optimizing Neural Networks for TinyML - Evaluation

This repository contains the raw data (`data`) for the figures (`figures`) and tables of the paper *Measuring what Really Matters: Optimizing Neural Networks for TinyML* ([arXiv:2104.10645](https://arxiv.org/abs/2104.10645)).


## Installation

```
pip install -r requirements.txt
```


## Usage

```
jupyter lab
```

You will be automatically redirect to your browser where you can explore the notebooks with Jupyter lab.
`01_Figures.ipynb` contains the code for reproducing the figures from the raw data. `02_Tables.ipynb` contains the code for investigating the latency per operation which is presented in Section 4.3.
The resulting figures are exported as `.pdf`.


## Relevant Repositories


- [Master Repository](https://gitlab.ethz.ch/tec/public/tflm-toolchain/)
    - [Models used for our experiments](https://gitlab.ethz.ch/tec/public/tflm-toolchain/tflm-models)
    - [Toolchain](https://gitlab.ethz.ch/tec/public/tflm-toolchain/tflm-toolchain)




## Cite as
```bibtex
@article{DBLP:journals/corr/abs-2104-10645,
  author    = {Lennart Heim and
               Andreas Biri and
               Zhongnan Qu and
               Lothar Thiele},
  title     = {Measuring what Really Matters: Optimizing Neural Networks for TinyML},
  journal   = {CoRR},
  volume    = {abs/2104.10645},
  year      = {2021},
  url       = {https://arxiv.org/abs/2104.10645},
  archivePrefix = {arXiv},
  eprint    = {2104.10645},
  timestamp = {Tue, 27 Apr 2021 14:34:45 +0200},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2104-10645.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```