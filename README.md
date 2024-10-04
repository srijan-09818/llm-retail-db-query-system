# NepTech Store: Talk to a Database  
![alt text](screenshot.png)
This is an end-to-end LLM project based on Langchain and Google Gemini (Generative AI). I developed a system that interacts with a MySQL database, allowing users to ask questions in natural language and receive answers by converting those queries into SQL statements, which are then executed on the database.
NepTech Store is a laptop store where they maintain their inventory, sales, and discounts data in the MySQL database. A store manager may ask questions such as:
- How many Asus laptops with 8GB RAM and 512GB SSD are left in stock?
- What will be the total sales value if I sell all laptops with i7 processors after applying discounts?

The system is intelligent enough to generate accurate queries for a given question and execute them on the MySQL database.


## Project Highlights

- NepTech Store sells laptops from brands like Dell, HP, Lenovo, Apple, and Asus.
- Their inventory, sales, and discount data are stored in a MySQL database.
- I built an LLM-based question and answer system that will use the following tools:
  - Google Gemini as Generative AI/LLM
  - Hugging Face embeddings
  - Streamlit for UI
  - Langchain framework
  - Chromadb as a vector store
  - Few-shot learning
- In the UI, the store manager will ask questions in natural language, and it will produce the answers with SQL Query for verification.
