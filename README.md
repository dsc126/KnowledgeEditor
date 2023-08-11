# KnowledgeEditor

Code for Editing Factual Knowledge in Language Models (https://arxiv.org/abs/2104.08164).

```bibtex
@inproceedings{decao2021editing,
  title={Editing Factual Knowledge in Language Models}, 
  author={Nicola De Cao and Wilker Aziz and Ivan Titov},
  journal={Proceedings of the 2021 Conference on Empirical Methods in 
           Natural Language Processing (EMNLP2021)},
  url={https://arxiv.org/abs/2104.08164},
  year={2021},
}
```

**Please consider citing our works if you use code from this repository.**

# Models and Data

This [folder](https://mega.nz/folder/p9JC3bwC#vzcrsh9b-pnWPaWdlcBVUA) contains the datasets and the base models used for this work.

# Installation

```
conda create -n KnowledgeEditor python=3.7
conda activate KnowledgeEditor
cd KnowledgeEditor
pip install torch==1.9.1+cu111 torchvision==0.10.1+cu111 torchaudio==0.9.1 -f https://download.pytorch.org/whl/torch_stable.html
pip install -r requirement.txt
```
