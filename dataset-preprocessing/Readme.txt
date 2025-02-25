|- Kurdish Sorani Dataset Preprocessing -|
******************************************

Scripts for cleaning and normalizing Kurdish Sorani text data for NER tasks.
******************************************

> Features
  - English word/character removal
  - English to Kurdish Sorani numeral conversion 
  - Text tokenization using KLPT

---------------|~Requirements~|-------------------
> Requirements
  - Python 3.7+
  - KLPT
  - python-docx
  - re

---------------|~USAGE~|-------------------
> Usage
  1. Place input text in `input.txt` or `input.docx`
  2. Run: `python preprocess.py`
  3. Get processed output in `output.txt`

---------------|~Script Details~|-------------------
> Script Details
  - `preprocess.py`: Main preprocessing pipeline
  - Input formats: .txt, .docx
  - Output: Space-separated tokens with 'O' tags

---------------|~Citation~|-------------------
> Citation
  If you use this preprocessing pipeline, please cite:
  [Add your paper citation here]
