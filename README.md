# Text Summarization Project

## Model Design:
- Designed three text summarization models:
  - Model 1: LSTM RNN encoder, decoder, and attention layer.
  - Model 2: Extends Model 1 with a pointer generator network.
  - Model 3: Builds on Model 2 with added coverage.

## Project Overview:
- Developed text summarization models, challenging yet rewarding.
- Improved summary accuracy, coherence, and comprehensiveness.
- Applications in news summarization and chatbot content generation.
- Opportunities for further NLP research and innovation.
- Contribution to the discourse on text summarization and AI-driven content generation.
- Note: Models would benefit from more data and epochs.

## Paper Reference:
- Inspired by 'Get to The Point: Summarization with Pointer Generator Networks' by Peter J. Lin (Google Brain), Abigail See (Stanford University), and Christopher D. Manning (Stanford University).
- Leveraged attention mechanisms and combined extractive and abstractive summarization techniques.
- Pointer Generator Networks produce informative and coherent summaries.

## Project Steps:
- Learned from the referenced thesis.
- Designed three models with attention layers, pointers, and coverage.
- Compared models with the author's using Rouge Score.

## Working with .ipynb Files:
- For efficient processing of large .ipynb files, run Jupyter Notebook with the command: `jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10`.

## Dataset:
- Utilized the 'Dailymail stories' dataset (smaller subset due to system limitations).
- Extracted relevant information and pre-processed the data.

## Model Building:
- Architecture includes Attention layers, RNN encoder, LSTM layers with dropout, and a decoder.
- Models were compiled and fitted with 10 epochs.

## Model Fitting and Testing:
- Model performance assessed with accuracy and loss graphs.
- Self-test conducted to calculate Rouge scores for evaluation.

## Conclusion:
- Models show promise in improving text summarization.
- Further data and epochs could enhance model performance.
- Contribution to the growing field of AI-driven content generation and summarization.

