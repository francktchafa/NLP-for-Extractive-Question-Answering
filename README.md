**NLP Application for Extractive Question Answering**

This repository presents an extractive question-answering (QA) framework utilizing Natural Language Processing (NLP) techniques on the bAbI dataset. By leveraging deep learning-based language models, the system learns to extract relevant answers from structured narratives, mimicking human comprehension in context-based QA scenarios. The model is fine-tuned to efficiently retrieve key facts, ensuring robust generalization across diverse tasks within the dataset.

**Example:**

question = "What is north of the museum?"

text = "Mum enjoys visiting the museum because our house is 5 minutes north of the museum. "

answer = predict_answer(model, tokenizer, question, text)


**Answer:** House
