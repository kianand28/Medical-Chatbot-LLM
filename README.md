# Medical-Chatbot-LLM

# How to run?
### STEPS:

Clone the repository

```Command prompt
Project repository: https://github.com/
```
### STEP 01- Create a conda environment 

```Command prompt
conda create -n venv python=3.10 -y
```

```Command prompt
conda activate venv
```


### STEP 02- install the requirements
create the requirements.txt file in the root directory

```Command prompt
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```Command prompt
# run the following command to store embeddings to pinecone
python store_index.py
```

```Command prompt
# Finally run the following command
python app.py
```

Now,
```command prompt
open up localhost:
```
