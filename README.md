# README

## Requirements

### Hardware

Google Colaboratory
* CPU: Intel(R) Xeon(R) CPU @ 2.00GHz
* RAM: 53,469,676[KB]
* GPU: NVIDIA Tesla T4


### OS

Ubuntu 22.04.4 LTS (Jammy Jellyfish)


### Third party software

To use GPU, following packages are required.
* CUDA 12.5.82
* cuDNN 9.3.0

Above packages are pre-installed in Google Colaboratory. And following additonal python packages are needed.
* bitsandbytes 0.45.5
* langchain-community 0.3.24
* langchain-huggingface 0.2.0
* pdfminer.six 20250506
* chromadb 1.0.9


## How to run

Since the following files are in jupyter notebook format and can be run in Google Colaboratory or equivalent environment.
* `notebook/rag_with_quantized_llm.ipynb`
