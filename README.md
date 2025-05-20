An NLP project uses LLM for classify interview email as "Pass" or "Failed"

In this project we used 2 models:

1. We build context vectors from scratch and then feed them to GPT2 model, replacing the last layer to be classified layer. Source interview_email_llm.ipynb
2. We use BART model. Source BART_Suji.ipynb
