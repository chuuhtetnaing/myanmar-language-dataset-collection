# Myanmar Language Dataset Collection
This repository serves as a collection of Myanmar language datasets, focusing on both speech and text resources. Given 
the scarcity and difficulty in finding Myanmar language datasets, our goal is to create a centralized reference point for 
researchers, developers, and language enthusiasts. As Myanmar language resources are often challenging to locate, we 
encourage contributions from the community. 

If you know of or have access to additional Myanmar language datasets not 
listed here, please consider contributing by submitting a pull request or opening an issue. Let's collaborate to build 
a comprehensive inventory of Myanmar language resources.

## Myanmar Langauge Speech Dataset

1. Myanmar Speech Dataset for ASR
   - This is a collection of available Myanmar speech datasets for training ASR models.
   - Datasets in this collection:
     - OpenSLR (See No.2)
     - Google Fleurs (See No.4)
   - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-speech-dataset-for-asr)

2. Crowdsourced high-quality Burmese speech dataset (SLR80)
   - [Download Page](https://www.openslr.org/80/)
   - [Download Link](https://www.openslr.org/resources/80/my_mm_female.zip)
   - [HuggingFace Original Dataset](https://huggingface.co/datasets/openslr/openslr)
   - [HuggingFace Myanmar Language Only Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-speech-dataset-openslr-80)
   - [Notebook](Crowdsourced%20Burmese%20Speech%20Dataset/train-test-split.ipynb) (Train/Test splitting and uploading to huggingface)   

3. BloomSpeech
   - [HuggingFace Dataset](https://huggingface.co/datasets/sil-ai/bloom-speech)
   - [Notebook](BloomSpeech/load-myanmar-language.ipynb) (Loading Myanmar Language)
   - *Notes:* Although it's showing burmese, the actual `language='mya'` is Palaung (De'ang / Ta'ang / Riang) language.

4. Google Fleurs
   - [HuggingFace Original Dataset](https://huggingface.co/datasets/google/fleurs)
   - [HuggingFace Myanmar Language Only Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-speech-dataset-google-fleurs)
   - [Notebook](Google%20Fleurs/load-myanmar-language.ipynb) (Loading Myanmar language and uploading to huggingface)

## Myanmar Langauge Text Dataset

1. Asian Language Treebank (ALT)
   - [Download Page](https://www2.nict.go.jp/astrec-att/member/mutiyama/ALT/)
   - [HuggingFace Dataset](https://huggingface.co/datasets/mutiyama/alt)
   - It supports translation between following languages:
     - Myanmar (Burmese) To Bengali 
     - Myanmar (Burmese) To English
     - Myanmar (Burmese) To Filipino
     - Myanmar (Burmese) To Hindi
     - Myanmar (Burmese) To Bahasa Indonesia
     - Myanmar (Burmese) To Japanese
     - Myanmar (Burmese) To Khmer
     - Myanmar (Burmese) To Lao
     - Myanmar (Burmese) To Malay
     - Myanmar (Burmese) To Thai
     - Myanmar (Burmese) To Vietnamese
     - Myanmar (Burmese) To Chinese (Simplified Chinese).
2. A Corpus of Modern Burmese
   - [Download Page](https://live.european-language-grid.eu/catalogue/corpus/940/download/)
   - You can [download it directly](./A%20Corpus%20of%20Modern%20Burmese/allfiles.txt) from the current repo
3. Myanmar Spoken and Written Language Dataset
   - [HuggingFace Dataset](https://huggingface.co/datasets/kalixlouiis/myanmar-written-spoken-classification)
4. Myanmar NRC Format Dataset
   - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-nrc-format-dataset)
   - [Github Repo](https://github.com/chuuhtetnaing/myanmar-nrc-format-dataset)
5. Myanmar Wikipedia Dataset
   - Officail wikimedia/wikipedia Repo - [HuggingFace Dataset](https://huggingface.co/datasets/wikimedia/wikipedia) (subset: 20231101.my)
   - Alternative Repo with category paths
      - [HuggingFace Dataset](https://huggingface.co/chuuhtetnaing/myanmar-wikipedia-dataset)
      - [Github Repo](https://github.com/chuuhtetnaing/myanmar-wikipedia-dataset) with web crawler scripts/notebooks
6. Myanmar Book Corpus Dataset (MM-Lib)
   - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/mm-lib-book-dataset)
7. Myanmar C4 Dataset (Converted Zawgyi to Unicode)
   - Official C4 Repo - [HuggingFace Dataset](https://huggingface.co/datasets/allenai/c4)
   - Myanmar Unicode C4 Repo
      - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-c4-dataset)
      - [Unicode Conversion Notebook](allenai-c4/convert-zawgyi-to-unicode.ipynb)
8. Myanmar CulturaX Dataset (Converted Zawgyi to Unicode)
    - Official CulturaX Repo - [HuggingFace Dataset](https://huggingface.co/datasets/uonlp/CulturaX)
    - Myanmar Unicode CulturaX Repo
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-culturax-dataset)
        - [Unicode Conversion Notebook](uonlp-CulturaX/convert-zawgyi-to-unicode.ipynb)
9. Myanmar CC100 Dataset (Converted Zawgyi to Unicode)
    - Official CC100 Repo - [HuggingFace Dataset](https://huggingface.co/datasets/statmt/cc100)
    - Myanmar Unicode CC100 Repo
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-cc100-dataset)
        - [Unicode Conversion Notebook](statmt-cc100/convert-zawgyi-to-unicode.ipynb)
10. ChannelMyanmar Movie Summary Dataset
    - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/channelmyanmar-movie-summary-dataset)
11. Myanmar Fineweb2 Dataset (Converted Zawgyi to Unicode)
    - Official Fineweb2 Repo - [HuggingFace Dataset](https://huggingface.co/datasets/HuggingFaceFW/fineweb-2)
    - Myanmar Unicode Fineweb2 Repo
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-fineweb-2-dataset)
        - [Unicode Conversion Notebook](fineweb-2/convert-zawgyi-to-unicode.ipynb)