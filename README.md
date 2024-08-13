﻿# End-to-End RAG App

I have applied RAG on Holy Quran Text.
## Steps
1. Downloaded dataset from kaggle
2. Cleaned data
3. Locally stored cleaned data
4. Created vectordb from the data and stored in locally
5. Used similarity_search to find relevant docs
6. Created a prompt with context from vectordb and query
7. Used LLM 'gpt-2-xl' to generate response of query
8. Used gradio to build an interface
9. Deployed the app on huggingface

Huggingface space : https://huggingface.co/spaces/defoxtrotalpha/Ask-Holy-Quran
