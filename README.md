# vanilla_chat

# How to run
### STEPS:

Clone the repository

```bash
git clone https://github.com/19-17-17-19-14/vanilla_chat.git
```

### STEP 01 - Create conda environment

```bash
conda create -n my_env_name python3.12 -y
```

```bash
conda activate my_env_name
```

### STEP 02 - Install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add pinecone and openai keys:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# Store embeddings to pinecone.
python store_index.py
```

```bash
# ...and run.
python app.py
```

```bash
open up localhost:
```

### Tech Stack:

- Python
- LangChain
- Flask
- GPT
- Pinecone

### Notes
- [Generative AI for Developers – Comprehensive Course](https://www.youtube.com/watch?v=F0GQ0l2NfHA) on YouTube.
- Original [source](https://github.com/entbappy/Generative-AI-Mastery-Resources/tree/main/End%20to%20End%20Projects).