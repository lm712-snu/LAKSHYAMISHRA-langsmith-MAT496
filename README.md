# LAKSHYAMISHRA-langsmith-MAT496

# 🧠 LAKSHYA MISHRA-2310110163-MAT496-Monsoon2025 — LangSmith Learning Repository

This repository documents my complete learning journey through the **LangSmith** modules as part of **MAT495 - Monsoon 2025**.  
It includes all notebooks, screenshots, experiments, and code implementations demonstrating concepts like tracing, evaluation, and experimentation in LangSmith.

> 💡 Each commit message corresponds to video-wise learnings and incremental notebook improvements.  
> Screenshots of the LangSmith Dashboard are also included to showcase tracing runs, dataset creation, evaluators, and experiments.

---

## 📘 Overview

This repository is divided into **modules**, mirroring the structure of the LangSmith training curriculum.

- **Module 0** – Retrieval-Augmented Generation (RAG) Application  
- **Module 1** – Tracing and Monitoring  
- **Module 2** – Experiments and Evaluation  

Each module contains my **personal implementation notebooks** and the corresponding **original tutorial versions** for comparison.

---

## 📦 Repository Structure

├── intro-to-langsmith-my-version/ # My implementations
│ ├── notebooks/
│ │ ├── module_0/ # RAG application
│ │ ├── module_1/ # Tracing and Monitoring
│ │ └── module_2/ # Experiments and Evaluation
│
├── intro-to-langsmith-original/ # Original tutorial notebooks
│
├── requirements.txt # Python dependencies
└── README.md # This file

CREATING A VIRTUAL ENVIRONMENT
python -m venv .venv
.venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Set Up Environment Variables

Create a .env file in the project root:

OPENAI_API_KEY=your_openai_api_key_here
LANGCHAIN_TRACING_V2=true
LANGCHAIN_API_KEY=your_langchain_api_key_here
LANGCHAIN_PROJECT=LangSmith-MAT496

🧮 Key Features Across Modules
Category	Description
Environment Setup	Configured LangSmith + OpenAI API
Tracing	Decorator-based tracing for LLM calls
Evaluation	Custom evaluators and scoring
Experimentation	A/B testing, pairwise comparisons
Visualization	Dashboard metrics and analytics
Versioning	Dataset and experiment version control

🧰 Dependencies
Package	Description
langchain	Core framework for building LLM applications
langchain_openai	OpenAI embedding and model integrations
langsmith	Experiment tracking, tracing, and evaluation
openai	API interface for OpenAI models
tiktoken	Tokenization and chunking
scikit-learn	Vector similarity calculations
python-dotenv	Environment variable management

🧪 Usage Notes
Each notebook is self-contained and can be run independently.

Make sure environment variables are properly configured before execution.

Some cells may require internet access (for model calls and LangSmith tracing).

Follow the notebook order for the best learning flow.

📸 Dashboard Previews
Screenshots in /screenshots/ show:

Tracing views

Run types

Experiment dashboards

Evaluator setups

Dataset management

Comparative results

🔍 Repository Link
📦 Main Repository:
👉LAKSHYA MISHRA - 2310110163 -MONSOON2025LLM

🧑‍💻 Author
LAKSHYA MISHRA
Student — MAT496, Monsoon 2025
Shiv Nadar University
📧 [LM712@SNU.EDU.IN]

🪄 License
This project is distributed under the MIT License.
Feel free to explore, modify, and extend the work for educational or research purposes.

🌐 References
LangSmith Documentation

LangChain GitHub Repository

OpenAI API Documentation



---

Would you like me to also generate a matching `requirements.txt` (auto-detected from your LangSmith and LangChain notebooks)?  
It’ll make the repository fully ready for evaluation and setup on any system.

