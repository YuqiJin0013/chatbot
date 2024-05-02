# Deep learning chatbot project
## Team Members
* Yuqi Jin
* Rana Ritesh
* Sai Yasasvi Dutt Malladi (Yash)
  
## Dataset
* dialogs.txt which consists of questions and answers, which involve opinions, preferences, and personal experiences 
* The way of creating our own dataset is to write our own examples and responses for 20 lines, then we use AI tool to generate the rest thousands lines
* The train_data.csv which has been tockenized the dialogs.txt by adding <eos> and <sos> for each sequence.
  
## Approach
Implement the following models to accomplish the interaction of chatbot
* Seq2Seq model (keras_seq2seq_model.ipynb)
* Transformer model (Transformer_model.ipynb)

## Presentation Slides Link
https://docs.google.com/presentation/d/1i-PE9bpb8WS-UreJv23ItzlQcMtA9nyLwyAFWNCOXxw/edit?usp=sharing

## Installation Instructions
Highly recommend run on Google Colab.
Steps shown below 
* git clone (Clone the repository to your local machine)
* cd repository
* python -m venv venv :Create a virtual environment (optional but recommended)
* venv\Scripts\activate (Windows) | source venv/bin/activate (Mac/Linux)
* pip install -r requirements.txt
* navigate the repo
* run files in your terminal or use Google Colab, vscode or others 





