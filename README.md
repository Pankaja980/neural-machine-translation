# Real-Time Language Translation (NMT)

This is a simple **Streamlit-based** application for real-time language translation using **Neural Machine Translation (NMT)** model.

## Features
- Supports multiple language translations.
- Uses a dataset for quick lookups.
- Falls back to Hugging Face models if no dataset match is found.
- Simple and user-friendly **web interface**.

## Installation
```bash
pip install streamlit transformers torch pandas
```

##  Run the App
```bash
streamlit run app.py
```

##  Files
- `app.py` - Main Streamlit app
- `large_multilingual_translation_dataset.csv` - Translation dataset
- `README.md` - Project documentation

##  Credits
Built with **Streamlit**, **Hugging Face Transformers**, and **Pandas**.

