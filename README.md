# 🔍 Smart Research Planning & Summarization Tool

An AI-powered research planning agent built with the **LangChain ecosystem**. This tool automates literature review, performs multi-step research, summarizes findings, and generates structured reports — helping researchers, students, and professionals save time and gain insights faster.



---

## 🚀 Features

- 🧠 **Automated Research Planning**  
  Generate intelligent research plans based on a user-defined topic or query.

  ![Screenshot 2025-05-01 103403](https://github.com/user-attachments/assets/8aea7fa8-863e-4eaf-8df3-ff6966e2d460)


- 📚 **Source Retrieval & Summarization**  
  Collect data from web sources, academic papers and summarize key points using LLMs.

  ![Screenshot 2025-05-01 103718](https://github.com/user-attachments/assets/8da4ddf5-329c-4025-bd56-1884424b09ca)


- 📝 **Report Generation**  
  Outputs structured summaries or research briefs in Markdown or PDF.

  ![Screenshot 2025-05-01 104011](https://github.com/user-attachments/assets/8dd43a5d-9f0e-432f-9f42-bf96ec93f2b1)


- 🔁 **LangGraph Integration**  
  Enables multi-step, memory-aware agent workflows.

- 🌐 **LangServe API**  
  Easily serve your research agent via an HTTP API endpoint.

- 📊 **LangSmith Debugging**  
  Monitor, trace, and debug complex agent behavior and LLM responses.

  ![Screenshot 2025-05-01 104037](https://github.com/user-attachments/assets/ef513e7e-c99e-4560-9749-c9d4a78797f3)


---

## 🛠️ Built With

- [LangChain](https://www.langchain.com/)
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [LangServe](https://github.com/langchain-ai/langserve)
- [LangSmith](https://smith.langchain.com/)
- OpenAI API (LLMs)
- Python 3.10+

---

## 📦 Installation

```bash
conda create -n myenv python==3.11 -y 

conda activate myenv

pip install -r requirements.txt


# run the project 


uvicorn langserve_app:app --reload
python sdk_client.py
streamlit run streamlit_app.py

http://localhost:8000/summarize/playground/ 
http://localhost:8000/research/playground/  
