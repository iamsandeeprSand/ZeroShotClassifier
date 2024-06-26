# Zero-Shot Text Classification App   

https://www.youtube.com/watch?v=v1tBMj-OPDs

This repository contains a Streamlit application for zero-shot text classification using Hugging Face's Transformers library. The app allows users to input text and a set of labels, and it predicts the likelihood of each label for the given text.

## Features

- **Zero-Shot Text Classification**: Classify text into user-defined labels without any prior training on the specific labels.
- **Interactive UI**: Easy-to-use interface built with Streamlit.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Installation

1. Install the required packages:

   ```sh
   pip install streamlit transformers
   ```

### Usage

1. **Enter Text**: Input the text you want to classify in the "Enter text to classify:" field.
2. **Enter Labels**: Input the labels you want to use for classification, separated by commas, in the "Enter comma-separated labels:" field.
3. **View Results**: The app will display the likelihood of each label for the given text.

## Example

### Input

- **Text**: "The new iPhone has amazing features and a sleek design."
- **Labels**: "technology, sports, entertainment, politics"

### Output

```
- **technology**: 0.9754
- **entertainment**: 0.0173
- **sports**: 0.0056
- **politics**: 0.0017
```


## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)

![image](https://github.com/iamsandeeprSand/ZeroShotClassifier/assets/139530620/ba36931b-1415-4398-b760-d664b0b21b22)

https://www.youtube.com/watch?v=v1tBMj-OPDs

