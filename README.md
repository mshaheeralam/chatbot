# Chatbot-using-OpenAI-API
 A chatbot which is trained on a text of the book and gives relevant answers when questioned related to the book. It uses Ada-002 embedding model to generate embeddings and for question answering it uses GPT 3.5 Turbo.

Following are the steps to implement this system:
1. Generate Embeddings
  - Run generate_embeddings.py. Remember to enter you OPENAI API Key in every py file.
  - This should generate a file pages_with_embeddings.json
  - If you are unable to run the generate_embeddings.py due to token limit, its totally fine.
  - I have attachted the embeddings that are generated with the name 'pages_with_embeddings.json'.
  - Convert this json file into parquet which is done by running json_to_parquet.ipynb
 
2. Test Time
  - Now you are good to go and run the main.py.
  