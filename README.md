
# 🩺 Medical Text Analysis System
## Overview
The Medical Text Analysis System is a cutting-edge platform that leverages Natural Language Processing (NLP) to simplify and automate insights extraction from complex medical texts. Built using advanced machine learning models like PubMedBERT and frameworks such as Streamlit, this system addresses key challenges in processing healthcare data for clinicians, researchers, and healthcare professionals.
Features
## 🌟 Core Functionalities
1.	Text Summarization
o	Summarizes lengthy medical abstracts into concise and clinically relevant overviews using PubMedBERT.
2.	Named Entity Recognition (NER)
o	Extracts critical medical entities (diseases, medications, procedures) using a biomedical NER model.
3.	Interactive Q&A System
o	Provides real-time answers to medical questions using a locally deployed Ollama server with the Llama 2 model.
4.	Multilingual Translation
o	Translates medical text into multiple languages using the Google Translation API, improving accessibility worldwide.
5.	Sentiment Analysis
o	Analyzes sentiments in medical texts to provide actionable insights and visualize them with intuitive charts.
________________________________________
## System Architecture
The system is built on a three-layer modular architecture:
1.	Input Layer:
o	Supports multiple formats like PDF, TXT, and ZIP files for flexible data ingestion.
2.	Core Processing Layer:
o	Incorporates pre-trained models like PubMedBERT for summarization, d4data/biomedical-ner-all for NER, and Hugging Face pipelines for sentiment analysis.
3.	Integration Layer:
o	A user-friendly Streamlit web interface ensures seamless visualization and interaction with insights.
 ________________________________________
### Tech Stack
Frameworks & Libraries
•	Streamlit: For building the interactive web app.
•	PyMuPDF (Fitz): For PDF text extraction.
•	Hugging Face Transformers: For NER, summarization, and sentiment analysis.
•	PubMedBERT: Domain-specific summarization model.
•	Ollama Server: For hosting the Q&A chatbot.
•	Google Cloud Translation API: For real-time text translation.
Languages
•	Python
________________________________________
# 🛠️ Setup Instructions

## Clone the Repository
Run the following commands to clone the repository and navigate to the project directory:

```bash
git clone https://github.com/SATHEESH-MEADI/MediText-Summarizer.git
cd medi-text-summarizer


________________________________________
Dataset
The dataset, sourced from https://github.com/JohnSnowLabs, contains 1,000 text files focusing on various medical conditions.
________________________________________
Key Highlights
•	Privacy-Centric: The Q&A module runs locally using the Ollama server to ensure data privacy.
•	Scalable Design: Handles large datasets efficiently with chunk-based text processing.
•	Global Accessibility: Supports multilingual translation for non-English-speaking users.
________________________________________
Future Enhancements
•	Text-to-Speech (TTS): Integrating TTS models to deliver audio summaries.
•	Avatar-Based Interaction: Adding a virtual assistant for enhanced engagement.
•	Expanded Multilingual Q&A: Supporting multi-language queries and responses.
________________________________________
Credits
This project was developed as part of DATA 690 - Introduction to NLP at the University of Maryland Baltimore County (UMBC) under the mentorship of Dr. Antony Diana.

Team Members:

•	Satheesh Meadi

•	Nishanth Hanmanthureddygari
________________________________________
License
This project is licensed under the MIT License.
________________________________________
Connect
We’d love your feedback! Feel free to raise issues, fork the project, or connect with us on 

📚 LinkedIn: https://www.linkedin.com/in/srilakshmi-pyarsani

📧 Email: Srilakp1@umbc.edu



________________________________________


