# PhishGuard-AI-Email-Phishing-Detection
AI-Based Email Phishing Detection using BERT

## Trained Model
The trained BERT model is not included in this repository because it exceeds GitHub's file size limits.
To generate the model:
1. Open the notebook in Google Colab.
2. Run all cells.
3. The notebook will automatically train and save the model as `phishguard_bert_model`.

## Alternate Method - Trained Model
Download the trained model from:
[https://drive.google.com/...](https://drive.google.com/drive/folders/1k5DB2Rf28MjyYwa8i2SORMDQ16dYql4V?usp=sharing)

After downloading, place the folder in the project directory before running predictions.

## Project Execution
# PhishGuard: AI-Based Email Phishing Detection Using BERT
## Live Demo
A temporary Gradio demo is available at:
**https://2fa49d63ef1da5864d.gradio.live**
> **Note:** This is a temporary Gradio share link and may expire automatically. If the link is unavailable, please open the Google Colab notebook, run all cells, and a new Gradio link will be generated. :contentReference[oaicite:1]{index=1}
---
## How to Run
1. Open the `PhishGuard.ipynb` notebook in Google Colab.
2. Upload the dataset (`phishing_email_dataset.csv`).
3. Run all cells sequentially.
4. The notebook will train the BERT model.
5. A Gradio web interface will launch automatically.
6. Paste an email into the text box and click **Submit** to classify it as **Legitimate** or **Phishing**.
---
## Features
- AI-powered phishing email detection using BERT
- Confidence score
- Risk level assessment
- Suspicious keyword detection
- Accuracy, Precision, Recall, and F1-score
- Confusion Matrix
- ROC Curve
- Interactive Gradio interface
---
## Technologies Used
- Python
- BERT (Transformers)
- PyTorch
- Scikit-learn
- Gradio
- Pandas
- Matplotlib
