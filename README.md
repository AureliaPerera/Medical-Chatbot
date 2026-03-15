# End-to-End-Medical-Chatbot

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/entbappy/End-to-End-Medical-Chatbot
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```


```bash
conda activate medibot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

Create a .emv file in the root directory and add your Pinecone & openai credentials as follows. 

PINECONE_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXX"
OPENAI_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXX"

### run the following command to store embeddings to pinecone
python store_index.py

### Finally Run the following command
python app.py
