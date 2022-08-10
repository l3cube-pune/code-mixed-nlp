# L3Cube-HingCorpus
L3Cube-HingCorpus is the first large-scale real Hindi-English code mixed data in a Roman. It consists of 52.93M sentences and 1.04B tokens, scraped from Twitter.
We also present HingBERT, HingMBERT, HingRoBERTa, and HingGPT. The BERT models have been pre-trained on codemixed HingCorpus.
The evaluation details are mentioned in our paper <a href='https://arxiv.org/abs/2204.08398'> link </a>.

The full HingCorpus(roman) is shared <a href='https://drive.google.com/file/d/1s_6eHO9zDhxQ-xVN1TyNguszV1meZkl9/view?usp=sharing'> here </a>.

## Hing BERT models and Hing Fast Text model

|Model|Description|Link|
|:--------:|:----:|:----:|
|HingBERT|Base-BERT|<a href='https://huggingface.co/l3cube-pune/hing-bert'> roman </a>|
|HingRoBERTa|RoBERTa|<a href='https://huggingface.co/l3cube-pune/hing-roberta'> roman </a>, <a href='https://huggingface.co/l3cube-pune/hing-roberta-mixed'> roman + devanagari </a>|
|HingMBERT|mBERT|<a href='https://huggingface.co/l3cube-pune/hing-mbert'> roman </a>, <a href='https://huggingface.co/l3cube-pune/hing-mbert-mixed'> roman + devanagari </a>|
|HingGPT|GPT2|<a href='https://huggingface.co/l3cube-pune/hing-gpt'> roman </a> <a href='https://huggingface.co/l3cube-pune/hing-gpt-devanagari'> devanagari </a>|
|HingFT|Fast Text|<a href='https://drive.google.com/file/d/1sNrXOcn31CWYj7d9iHOO8y0dTQa6qdWX/view?usp=sharing'> link </a>|

## L3Cube-HingLID

The L3Cube-HingLID is the Hindi-English code-mixed language identification dataset. It consists of 31756, 6420, and 6279 train, test, and validation samples respectively. The dataset is shared in the folder L3Cube-HingLID/.
The HingBERT-LID model is shared <a href='https://huggingface.co/l3cube-pune/hing-bert-lid'> here </a>.

## License

L3Cube-HingCorpus, and L3Cube-HingLID is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Citing
```
@article{nayak2022l3cube,
  title={L3Cube-HingCorpus and HingBERT: A Code Mixed Hindi-English Dataset and BERT Language Models},
  author={Nayak, Ravindra and Joshi, Raviraj},
  journal={arXiv preprint arXiv:2204.08398},
  year={2022}
}
```

This project is co-ordinated and mentored by <a href='https://www.linkedin.com/in/ravirajoshi/'> Raviraj Joshi </a> under L3Cube Pune. For any queries contact ravirajoshi@gmail.com .

