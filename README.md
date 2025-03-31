
# 📚 **Semantic Book Recommender with LLMs**

I built this project to create a **semantic book recommender** that uses Large Language Models (LLMs) to suggest books based on natural language queries. The goal is to let users describe the type of book they want (like *"a thrilling adventure with unexpected twists"*) and get relevant, emotion-based recommendations.

---

## 🚀 **Project Overview**

This project has five key components:

### 1. 🧹 **Text Data Cleaning**
Cleaned and pre-processed the book descriptions to ensure high-quality input for embeddings.

### 2. 🧠 **Vector Search with a Vector Database**
Built a vector database with **semantic search** to retrieve the most similar books based on user queries.

### 3. 📚 **Zero-Shot Text Classification**
Used **zero-shot classification with LLMs** to categorize books as *"fiction"* or *"non-fiction"*, allowing for filtered results.

### 4. 🎭 **Sentiment Analysis and Emotion Extraction**
Extracted emotional tones (like *joy*, *sadness*, *fear*, etc.) from book descriptions, giving users the option to refine results by the mood of the book.

### 5. 🌐 **Gradio Web Application**
Developed an interactive interface with **Gradio** where users can enter book descriptions and receive personalized recommendations.

---

## 🛠️ **Tech Stack & Dependencies**

Built with **Python 3.11**, the project leverages the following libraries:

- `kagglehub` – For dataset retrieval  
- `pandas` – For data manipulation  
- `matplotlib` & `seaborn` – For visualizations  
- `python-dotenv` – For managing environment variables  
- `langchain-community` – For LLM pipelines  
- `langchain-chroma` – For semantic search  
- `transformers` – For embeddings and sentiment analysis  
- `gradio` – For building the web interface  

---

## 📥 **Dataset Information**
The book data is sourced from **Kaggle**. The dataset includes book descriptions, author information, and emotional scores, providing a rich foundation for recommendations.

--- 

Feel free to explore the code, try it out, and adjust the recommendations to your liking.
