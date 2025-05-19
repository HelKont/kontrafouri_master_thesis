# Subjectivity Mispredictions of LLAMA and BERT

This repository contains the code, data, and resources used in my Master's thesis, which investigates how large language models, specifically LLAMA and BERT, handle subjectivity in natural language and where they fail.

## Thesis Overview

The thesis explores:
- How LLAMA and BERT models differ in their handling of subjective versus objective language.
- Common patterns of misprediction when evaluating sentence subjectivity.
- The role of lexical resources like NRC Subjectivity Lexicon and veridicality datasets in interpreting model behavior.

Two primary notebooks are used to structure the experiments:
- `thesis_notebook_SUBJ`: Focuses on analyzing model predictions against the SUBJ dataset.
- `thesis_notebook_news`: Applies models to real-world text, such as news content, to observe subjectivity trends and misclassifications.

## Models Used

- [LLAMA](https://huggingface.co/meta-llama/Llama-3.1-8B) (open-source large language model)
- [BERT](https://huggingface.co/bert-base-uncased) (Bidirectional Encoder Representations from Transformers)

## Repository Structure

├── LICENSE # Open source license \
├── README.md # This file\
├── nrc.csv # NRC Subjectivity Lexicon (words with subjectivity scores)\
├── subj_lex.csv # MPQA subjectivity lexicon (words and phrases annotated with subjectivity scores)\
├── thesis_notebook_SUBJ.ipynb # Notebook analyzing model behaviour on the SUBJ dataset\
├── thesis_notebook_news.ipynb # Notebook analyzing model behaviour on the news dataset\
├── veridicality.csv # Dataset used for evaluating veridicality in sentences\

## License
This project is licensed under the terms of the LICENSE file.

## Author
Eleni Kontrafouri\
Master's Thesis in Speech and Language Processing\
University of Konstanz, 2024
