# Transformer QA on Alice's Adventures in Wonderland 
## Question Answering with Transformers (HuggingFace + RoBERTa) 

This project builds a long-document Question Answering (QA) system using a pretrained transformer model from HuggingFace. The model processes Alice’s Adventures in Wonderland by Lewis Carroll, downloaded from Project Gutenberg in raw text form.

Because transformer models cannot read an entire novel at once, the text was cleaned, chunked, and paired with a retrieval step so the model can locate the most relevant passage before performing extractive QA.

### Key Skills
- Long-document preprocessing, cleaning, and texting chunking
- Keyword-based retrieval for selecting relevant text passages
- Transformer-based extractive QA using HuggingFace pipelines
- Hyperparameter tuning (chunk size, top_k retrieval, chunk overlap)
- Evaluating QA accuracy, confidence scoring, and model limitations
