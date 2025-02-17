
# IVGD: Invertible Validity-aware Graph Diffusion

This is an implementation of Invertible Validity-aware Graph Diffusion for the source localization problem, as described in paper:

[Junxiang Wang, Junji Jiang, and Liang Zhao. An Invertible Graph Diffusion Neural Network for Source Localization. (WWW 2022)](https://arxiv.org/abs/2206.09214)

## Requirement

scipy==1.5.0

torch==1.6.0

ipdb==0.13.4

numpy==1.18.5

scikit_learn==0.23.2

## Implementation

python pretrain.py # train the graph diffusion model.

python main.py # train the source localization model, which is the inverse of the graph diffusion model. 

## Citation

	@inproceedings{IVGD_www22,
    title     = {{An Invertible Graph Diffusion Neural Network for Source Localization}},
    author    = {Junxiang Wang, Junji Jiang, and Liang Zhao},
    booktitle = {Proceedings of the 31th International World Wide Web Conference (WWW 2022)},
    year      = {2022}
    }  
