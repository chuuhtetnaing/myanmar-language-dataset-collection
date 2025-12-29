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
     - MIG Burmese Audio (See No.5)
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

5. MIG Burmese Audio
   - [HuggingFace Dataset](https://huggingface.co/datasets/Ko-Yin-Maung/mig-burmese-audio-transcription)

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
12. Myanmar Dhamma Article Dataset (Converted Zawgyi to Unicode)
    - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/dhamma-article-dataset)
    - [Notebook](Dhamma%20Dataset/dhamma-q-and-a.ipynb) (Scraping notebook)   
13. Myanmar Dhamma Question and Answer Dataset
    - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/dhamma-question-answer-dataset)
    - [Notebook](Dhamma%20Dataset/dhamma-q-and-a.ipynb) (Genrating Q&A with Gemma 3)
14. Myanmar Aya Dataset
    - Official Aya Repo - [HuggingFace Dataset](https://huggingface.co/datasets/CohereLabs/aya_dataset)
    - Myanmar Aya Repo
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-aya-dataset)
        - [Dataset Generting Notebook](Myanmar%20Instruction%20Tuning%20Dataset/aya-dataset.ipynb)
15. Burmese Microbiology 1K
    - [HuggingFace Dataset](https://huggingface.co/datasets/jojo-ai-mst/Burmese-Microbiology-1K)
16. Mpox Myanmar
    - [HuggingFace Dataset](https://huggingface.co/datasets/jojo-ai-mst/Mpox-Myanmar)
17. Myanmar Agriculture 1K
    - [HuggingFace Dataset](https://huggingface.co/datasets/jojo-ai-mst/Myanmar-Agricutlure-1K)
18. Myanmar Instruction Tuning Dataset
    - This is a collection of available Myanmar Question and Answer datasets for instruction fine-tuning LLM models.
    - Datasets in this collection:
        - Burmese Microbiology 1K (See No.15)
        - Mpox Myanmar (See No.16)
        - Myanmar Agriculture 1K (See No.17)
        - Myanmar Aya Dataset (See No.14)
        - Myanmar Dhamma Question and Answer Dataset (See No.13)
        - Myanmar Football Dataset (See No.21)
        - Myanmar QnA Dataset v1 (See No.24)
    - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-instruction-tuning-dataset)
    - [Dataset Generting Notebook](Myanmar%20Instruction%20Tuning%20Dataset/combined-dataset.ipynb)
19. Myanmar Social Media Sentiment Analysis Dataset
    - Original Social Media Sentiments Analysis Dataset - [Kaggle Dataset](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset)
    - Myanmar Translated Dataset
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-social-media-sentiment-analysis-dataset)
        - [Translation Notebook](Social%20Media%20Sentiment%20Analysis/synthetic-data-generating.ipynb)
20. myXNLI - Myanmar Natural Language Inference Corpus
    - [HuggingFace Dataset](https://huggingface.co/datasets/akhtet/myanmar-xnli)
    - [Github Repo](https://github.com/akhtet/myXNLI)
    - [Paper](https://arxiv.org/abs/2504.09645)
21. Myanmar Football Dataset
    - [HuggingFace Dataset](https://huggingface.co/datasets/thisisfalse9/Myanmar_Football_Dataset)
    - [Kaggle Dataset](https://www.kaggle.com/datasets/thefalse9/myanmar-football-dataset)
    - [Github Repo](https://github.com/thisisfalse9/myanmar-football-dataset)
22. Myanmar Facebook Flores Dataset
    - Official Flores Repo - [HuggingFace Dataset](https://huggingface.co/datasets/facebook/flores)
    - Myanmar Facebook Flores Repo
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-facebook-flores-dataset)
        - [Dataset Generting Notebook](Facebook%20Flores/load-myanmar-language.ipynb)
23. Myanmar Text Segmentation Dataset
    - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-text-segmentation-dataset)
    - [Dataset Creation Notebook](Myanmar%20Text%20Segmentation/myanmar-text-segmentation-dataset.ipynb)
    - [Token Classification Fine-Tuning Notebook on this dataset](Myanmar%20Text%20Segmentation/myanmar-text-segmentation-fine-tuning.ipynb) which follows the [official token classification documentation](https://huggingface.co/docs/transformers/en/tasks/token_classification) from huggingface
    - Can test the Token Classification in this [Huggingface Space](https://huggingface.co/spaces/chuuhtetnaing/myanmar-text-segmentation-app)
24. Myanmar QnA Dataset v1
    - [HuggingFace Dataset](https://huggingface.co/datasets/freococo/myanmar_qna_dataset)
25. Myanmar POS Dataset
    - Original myPOS HuggingFace Dataset Repo - [HuggingFace Dataset](https://huggingface.co/datasets/LULab/myPOS)
    - Official myPOS GitHub Repo - [Github Repo](https://github.com/ye-kyaw-thu/myPOS)
    - Preprocessed and Cleanup Dataset Repo 
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-pos-dataset)
        - [Dataset Creation Notebook](myPOS/myanmar-pos-dataset-preparation.ipynb)
        - [Token Classification Fine-Tuning Notebook on this dataset](myPOS/myanmar-pos-fine-tuning.ipynb) which follows the [official token classification documentation](https://huggingface.co/docs/transformers/en/tasks/token_classification) from huggingface
        - Can test the POS Tagging in this [Huggingface Space](https://huggingface.co/spaces/chuuhtetnaing/myanmar-pos-app)
26. Myanmar-English News Translation Dataset
    - Original HuggingFace Dataset Repo - [HuggingFace Dataset](https://huggingface.co/datasets/Francis-Phone/mm_eng_news_translation)
    - Preprocessed and Cleanup Dataset Repo 
        - [HuggingFace Dataset](https://huggingface.co/datasets/chuuhtetnaing/myanmar-english-news-translation-dataset)
        - [Dataset Creation Notebook](MM-ENG-News-Translation/dataset-preparation.ipynb)
26. Myanmar OCR Datasets
    - [Myanmar OCR Dataset (7.6M)](https://huggingface.co/datasets/chuuhtetnaing/myanmar-ocr-dataset)
    - myOCR Dataset (23.9K)
      - [Preprocessed HuggingFace Image Dataset](https://huggingface.co/datasets/chuuhtetnaing/myOCR)
      - [Original Dataset](https://huggingface.co/datasets/LULab/myOCR)
      - [Original GitHub Repo](https://github.com/ye-kyaw-thu/myOCR)