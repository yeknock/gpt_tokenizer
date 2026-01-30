# Minimalistic Byte Pair Encoding (BPE) Tokenizer

A from-scratch implementation of the Byte Pair Encoding (BPE) algorithm, the standard tokenization method for modern LLMs (e.g., GPT-2, GPT-3 and Llama).





![Tokenizer](https://miro.medium.com/1*wOCxyFINp7GxvOTs56jlNQ.png)





## 🚀 Overview

Tokenization is the bridge between raw text and the numerical vectors processed by neural networks. This project implements a custom BPE tokenizer that handles UTF-8 byte-level encoding, frequent pair merging, and regex-based pre-tokenization.



**Key Features**

* UTF-8 Byte-Level Base: Starts with a base vocabulary of 256 bytes to ensure any text can be represented without "unknown" tokens.

* BPE Training: Logic to iteratively build a vocabulary by merging the most frequent adjacent pairs.

* Comparative Analysis: Includes a detailed comparison between GPT-2 and GPT-4 tokenization strategies.

* Validation: Built-in consistency checks to ensure 100% reversible encoding/decoding.





## 📂 Project Structure


``tokenizer.ipynb`` : The core Jupyter Notebook containing the implementation, training loops, and GPT-4 comparison benchmarks.





## How to Use?

1. Download the repository in your computer - ``git clone https://github.com/yeknock/gpt_tokenizer.git``
2. Move to the project directory
3. Open Jupyter Notebook
4. Run the code





## Questions ?

If you have any questions or suggestions, please contact me via gmail - yen.martirosyan@gmail.com









