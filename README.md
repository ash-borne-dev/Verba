# VERBA — Multilingual Text Translation

**Understanding Language. Connecting People.**

VERBA is an AI-powered multilingual text translation prototype built using Python and a pretrained Transformer-based language model. It aims to make translation accessible through a simple interface, with model inference performed locally.

## Features

- **Multilingual translation:** Translate text between supported languages.
- **Pretrained AI model:** Uses Meta's NLLB-200 distilled 600M model.
- **Simple interface:** An easy-to-use Gradio interface for entering and translating text.
- **Language selection:** Select source and target languages.
- **Translation benchmarking:** Measure translation performance across multiple test inputs.
- **Performance statistics:** Examine average, median, fastest, and slowest translation times.
- **Local inference:** The model runs on the local machine after its required files have been downloaded.

## Technology Stack

- Python
- Hugging Face Transformers
- Meta NLLB-200 (Distilled 600M)
- Gradio
- PyTorch

## How It Works

1. The user enters text and selects the source and target languages.
2. The input is processed using the model-compatible tokenizer.
3. The pretrained NLLB-200 model generates the translated text.
4. The translated result is displayed through the interface.
5. Benchmarking tools measure translation performance.

## Running the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/as-borne-dev/Verba.git
   ```

2. Open the project directory:

   ```bash
   cd Verba
   ```

3. Install the required dependencies:

   ```bash
   pip install torch transformers gradio sentencepiece
   ```

4. Open `VERBA_Development.ipynb` in Jupyter Notebook or Google Colab and execute the notebook cells in order.

**Note:** The pretrained model must be downloaded before its first use. Model download time and inference speed depend on your internet connection and hardware.

## Project Scope

VERBA is an academic project developed to explore practical applications of Natural Language Processing (NLP), Transformer architecture, tokenization, and pretrained multilingual models.

It demonstrates how an existing AI model can be integrated into a usable translation application rather than training a large language model from scratch.

## Limitations

- Translation quality depends on the pretrained model.
- Performance varies depending on available hardware.
- Translation quality may differ between language pairs.
- The project is a prototype and is not intended to replace professional translation services.

## Project Status

**Academic prototype — development and experimentation.**

---

*VERBA — Understanding Language. Connecting People.*
