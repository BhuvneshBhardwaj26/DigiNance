<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/2ae9de4c-de18-48ed-9076-c39e8df06c75" />
🧩 Problem Statement
Many individuals—especially those from rural or digitally underserved backgrounds—lack digital financial literacy. Challenges include understanding online payments (e.g., UPI), recognizing digital scams, calculating interest rates, or basic online personal budgeting. This knowledge gap can lead to fraud, poor money management, and digital exclusion for millions.

💡 Proposed Solution
An AI-powered agent, built using IBM Watsonx.ai, that provides trustworthy, document-grounded answers to questions about digital finance. With multilingual support and retrieval-augmented generation (RAG) from real financial documents, users can receive reliable, easy-to-understand guidance tailored to their needs.

🧠 Technologies Used
IBM Watsonx.ai Studio

IBM Granite Foundation Model (LLM)

Vector Index for Retrieval-Augmented Generation (RAG)

Financial PDFs (RBI, NPCI, etc.)

NLP (Natural Language Processing)

IBM Cloud Object Storage

☁️ IBM Cloud Services Used
Watsonx.ai Studio

IBM Granite Model

Watsonx Vector Index

IBM Cloud Lite Account

IBM Cloud IAM

IBM Cloud Object Storage

👥 End Users
General public seeking financial clarity

Rural and semi-urban citizens

Students and young professionals

First-time users of UPI/digital banking

NGOs and government outreach programs

Customer service centers

Self-Help Groups and Women’s Collectives

Educators and institutions

🌟 WOW Factors
Real RBI/NPCI (or uploaded) PDFs for answer grounding via RAG

End-to-end IBM Cloud & Watsonx stack

Graceful redirection for off-topic queries

Multilingual, inclusive, and future-ready

User education on scams, UPI, interest rates, budgeting, stock market, & more

Safe, personalized financial guidance

🧪 Key Features
Document-based financial Q&A via Vector Index

Powered by IBM Granite LLM for NLU

Integrated NLP features

Handles off-topic/irrelevant questions graciously

Tackles real concerns: digital fraud, loans/savings, UPI, etc.

🚀 How It Works
User submits a finance-related query (e.g., “How to avoid UPI fraud?”)

IBM Granite LLM processes natural language

Vector Index retrieves content from trusted, uploaded financial documents

AI agent delivers a grounded, user-friendly response


📌 How to Run or Deploy
Log into IBM Cloud Lite

Launch Watsonx.ai Studio

Create a new AI Agent

Upload financial PDFs to your Vector Index

Optionally, enable web search tools (Google, Wikipedia, etc.)

Set agent instructions/topics (restrict off-topic Q&A politely)

Test in preview panel

Deploy (web snippet, Streamlit, custom web UI)

🛣️ Future Scope
WhatsApp/mobile app integration

Voice-driven queries (speech-to-text)

Automated monthly report generation

Region-specific policy/news updates

Multilingual expansion via Watson Language Translator

🔗 Useful Links
https://cloud.ibm.com/registration
https://www.ibm.com/products/watsonx-ai
https://www.rbi.org.in/
https://skillsbuild.org/
⚖️ License
This project is licensed under the MIT License.

Created with as part of IBM SkillsBuild for Academia Internship 2025 by Bhuvnesh Kumar Bhardwaj

You can further personalize author info or links and add badges as needed!
