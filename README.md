# 💰 Personal Finance Chatbot  

The **Personal Finance Chatbot** is an intelligent conversational AI system that provides personalized financial guidance using **IBM Granite AI models**.  
It answers queries about **savings, taxes, and investments**, generates **budget summaries**, and offers **spending insights** through a simple web interface.  

---

## 🚀 Features  
- 💡 **Financial Guidance** – Get instant answers about savings, taxes, and investments.  
- 📊 **Budget Insights** – Generate summaries and actionable spending suggestions.  
- 🧠 **Adaptive Conversations** – Adjusts tone and complexity based on user queries.  
- ⚡ **Powered by IBM Granite** – Uses state-of-the-art generative AI models.  
- 🌐 **Web-based UI** – Built with Python and Gradio/Streamlit for easy interaction.  

---

## 🏗️ Project Architecture  
1. **User Interface (UI):** Gradio.  
2. **AI Engine:** IBM Granite LLM (from Hugging Face).  
3. **Processing Layer:** Python backend to handle queries and responses.  
4. **Deployment:** Runs locally or on cloud platforms for demos/hackathons.  

---

## 🏗️ Project Workflow (Google Colab)  
Since this project is built and executed in **Google Colab**, the workflow looks like this:  

**Colab Notebook Sections:**  
1. **Setup & Installation** – Install required libraries (transformers, gradio/streamlit, etc.).  
2. **Model Loading** – Load IBM Granite model from Hugging Face.  
3. **Chatbot Functionality** – Define functions to process user queries.  
4. **Interface** – Launch Gradio/Streamlit UI for interaction.  
5. **Demo** – Run chatbot and test queries.  

---

## 🛠️ Running on Google Colab  

1. Open the notebook in Google Colab.  
2. Run the **Setup** cell to install dependencies:  
   ```python
   !pip install transformers gradio streamlit
