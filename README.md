# Myanmar Language Dataset Collection
This repository serves as a collection of Myanmar language datasets, focusing on both speech and text resources. Given 
the scarcity and difficulty in finding Myanmar language datasets, our goal is to create a centralized reference point for 
researchers, developers, and language enthusiasts. As Myanmar language resources are often challenging to locate, we 
encourage contributions from the community. 

If you know of or have access to additional Myanmar language datasets not 
listed here, please consider contributing by submitting a pull request or opening an issue. Let's collaborate to build 
a comprehensive inventory of Myanmar language resources.

## Myanmar Langauge Speech Dataset

1. Crowdsourced high-quality Burmese speech dataset (SLR80)
   - [Download Page](https://www.openslr.org/80/)
   - [Download Link](https://www.openslr.org/resources/80/my_mm_female.zip)
   - [HuggingFace Original Dataset](https://huggingface.co/datasets/openslr/openslr)
   - [HuggingFace Myanmar Language Only Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-speech-dataset-openslr-80)
   - [Notebook](Crowdsourced%20Burmese%20Speech%20Dataset/train-test-split.ipynb) (Train/Test splitting and uploading to huggingface)   

2. BloomSpeech
   - [HuggingFace Dataset](https://huggingface.co/datasets/sil-ai/bloom-speech)
   - [Notebook](BloomSpeech/load-myanmar-language.ipynb) (Loading Myanmar Language)
   - *Notes:* Although it's showing burmese, the actual `language='mya'` is Palaung (De'ang / Ta'ang / Riang) language.

## Myanmar Langauge Text Dataset

1. Asian Language Treebank (ALT)
   - [Download Page](https://www2.nict.go.jp/astrec-att/member/mutiyama/ALT/)
   - [HuggingFace Dataset](https://huggingface.co/datasets/mutiyama/alt)
