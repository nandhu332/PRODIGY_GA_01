# GPT-2 Text Generation Web App

This repository contains a Python + Gradio app to generate text with a fine-tuned GPT-2 model.

# usage
python app.py
# then open http://127.0.0.1:7860/ in your browser
# Fine-tuning
1.Prepare custom_dataset.txt.
2.Uncomment the trainer.train() block in app.py.
3.Run python app.py to train and generate.
## Setup

```bash
python -m venv venv
source venv/bin/activate    # or .\venv\Scripts\activate.bat
pip install -r requirements.txt
