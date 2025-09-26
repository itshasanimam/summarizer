# summarizer
This project provides an interactive news article summarization tool built with Python, Hugging Face Transformers, and Jupyter/Colab notebooks.
## Features

- **Multiple summarization models**:
  - Pegasus (`google/pegasus-large`)
  - BART (`facebook/bart-large-cnn`)
  - Easily extendable to other transformer-based models

- **Interactive UI using ipywidgets**:
  - Enter a news article URL or paste text directly
  - Select the summarization model from a dropdown
  - Click a button to generate a concise summary
  - Clear input/output fields with a click

- **Supports long articles**:
  - Automatic truncation for model input limits
  - Optimized for GPU if available for faster summarization

- **Google Colab ready**:
  - Run directly in Colab without local setup
  - Supports GPU acceleration


## Installation

```bash
git clone https://github.com/itshasanimam/summarizer.git
cd summarizer
pip install -r requirements.txt
