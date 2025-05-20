Context: When we apply for jobs on Linkedin, Seek, etc. it takes time to open emails, read the content and check if they are either failed or passed status.

We created An NLP project uses LLM for classify interview email as "Passed" or "Failed"

Dataset can be found in email_dataset folder. We have 500 failed and 500 passed emails.

In this project we used 2 models:

1. We build context vectors from scratch and then feed them to GPT2 model, replacing the last layer to be classified layer. Source interview_email_llm.ipynb
2. We use BART model. Source BART_Suji.ipynb
