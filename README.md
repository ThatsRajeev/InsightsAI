## InsightsAI: Uncover Market Insights with Ease

**Introduction**

InsightsAI is a user-friendly news research tool designed to empower you with the knowledge you need to navigate the financial world. It simplifies information retrieval from news articles, allowing you to focus on extracting actionable insights.
![alt text]([http://url/to/img.png](https://github.com/ThatsRajeev/InsightsAI/blob/main/bot.jpg))

**Effortless Workflow:**
* **Load Articles:** Import article URLs directly or upload text files containing URLs. InsightsAI takes care of the rest.
* **Intelligent Processing:** Our system utilizes LangChain's UnstructuredURL Loader to extract text from web pages.
* **Powerful AI Integration:** OpenAI's embeddings create a unique fingerprint for each article's content, enabling efficient retrieval.
* **Lightning-Fast Search:** FAISS, a state-of-the-art search library, ensures you find the information you need instantly.
* **ChatGPT Assisted Insights:** Ask questions, and InsightsAI leverages ChatGPT's capabilities to provide answers along with relevant source URLs. Gain a deeper understanding of market trends and financial news.

**Benefits:**

* **Save Time:** Quickly find what you're looking for by bypassing tedious manual searches.
* **Make Smarter Decisions:** Gain a comprehensive understanding of financial news and market trends.
* **Stay Informed:** Effortlessly stay on top of critical market developments.
* **Simplify Research:** Extract valuable insights from news articles in a user-friendly interface.

**Getting Started:**

1. **Clone the Repository:**
```bash
git clone https://github.com/ThatsRajeev/InsightsAI.git
```

2. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

4. **Configure OpenAI API Key:**
   - Create a file named `.env` in the project root.
   - Add the line: `OPENAI_API_KEY=your_api_key_here` (Replace with your actual key).

5. **Run the Streamlit App:**
```bash
streamlit run main.py
```

**A Peek in Action:**

* Access the web app in your browser.
* Input URLs directly into the sidebar.
* Click "Process URLs" to initiate data loading and processing.
* Witness the system work its magic, splitting text, generating embeddings, and efficiently indexing with FAISS.
* All processed data gets stored and indexed for lightning-fast future retrieval.
* Ask questions related to the loaded news articles and receive answers along with source references.

**Project Structure:**

* `main.py`: The heart of the application, built with Streamlit.
* `requirements.txt`: Contains a list of required Python libraries.
* `faiss_store_openai.pkl`: Stores the FAISS index for efficient search.
* `.env` (Hidden): Houses your OpenAI API key securely.

**Let InsightsAI guide you on your path to financial success!**
