# Care-Reach-Medical-chatbot
Hi, this is my medical chatbot,"Carebot" that will be used by patients to ask their medical questions, and the bot will be able to give them a diagnosis based on the symptoms they have provided and will offer medication solutions to the illness diagnosed. This bot will be integrated in my mobile application.

# Steps on how to create and run the app;

First, clone the repository

```bash
Project repo: https://github.com/

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n carebot python=3.10 -y
```

```bash
conda activate carebot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
