# resume

%-------------------------
% Resume in LaTeX
% Based on the widely-used "Jake's Resume" template structure
% Compile with pdflatex
%-------------------------

\documentclass[letterpaper,10.5pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}

\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.6in}
\addtolength{\textwidth}{1.2in}
\addtolength{\topmargin}{-0.6in}
\addtolength{\textheight}{1.2in}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{
  \item\small{#1 \vspace{-2pt}}
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}[leftmargin=0.18in,itemsep=1pt]}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Arjun} \\ \vspace{3pt}
    \small Noida, India $|$ +91-9518169828 $|$ \href{mailto:kashyaparjun083@gmail.com}{kashyaparjun083@gmail.com} \\ \vspace{2pt}
    \small
    \href{https://www.linkedin.com/in/arjun-kashyap-181a45220/}{LinkedIn} $|$
    \href{https://my-portfolio-arjunk-01.vercel.app/}{Website} $|$
    \href{https://leetcode.com/u/Arjun4549/}{LeetCode} $|$
    \href{https://github.com/Arjun-0369-AI-ML-Developer}{GitHub} $|$
    \href{https://huggingface.co/ArjunKashyap369}{HuggingFace} $|$
    \href{https://www.kaggle.com/arjunninja}{Kaggle} $|$
    \href{https://tryhackme.com/p/Arjun0369}{TryHackMe}
\end{center}

%-----------SUMMARY-----------
\section{Professional Summary}
\small{AI/ML Developer with 2.5 years of experience building production-grade LLM systems. Optimized 4+ models including LLaMA, Mistral, and BERT, achieving 30--40\% accuracy improvements. Architected multi-agent chatbots using LangChain and LangGraph. Expertise in PyTorch, TensorFlow, RAG systems, and MLOps.}

%-----------EXPERIENCE-----------
\section{Professional Experience}
\resumeSubHeadingListStart

\resumeSubheading
{AI \& ML Developer}{June 2025 -- Present}
{In2IT Technologies}{Noida, Uttar Pradesh, India}
\resumeItemListStart
\resumeItem{Architected 3 production agentic chatbots with LangChain and LangGraph, reducing query resolution time by 40\%.}
\resumeItem{Optimized 5 LLaMA and Mistral models using LoRA and QLoRA techniques, improving task accuracy by 30--40\% over base models.}
\resumeItem{Designed RAG systems with FAISS and ChromaDB, cutting information retrieval time from 15 seconds to 6 seconds -- a 60\% reduction.}
\resumeItem{Implemented Webhook and WebSocket connections enabling real-time, event-driven communication between systems, ensuring reliable, low-latency data delivery across connected clients.}
\resumeItem{Configured Apache Kafka pipelines processing 100,000+ events per hour with 99.9\% uptime.}
\resumeItem{Collaborated with cross-functional teams to translate business requirements into scalable AI solutions, delivering 99\% successful projects.}
\resumeItem{Improved model inference latency by 45\% through quantization and deployment strategies using Docker.}
\resumeItemListEnd

\resumeSubheading
{AI \& ML Developer and Data Analyst Intern}{Nov 2023 -- Feb 2025}
{TechVidya Career Pvt. Ltd.}{Noida, Uttar Pradesh, India}
\resumeItemListStart
\resumeItem{Developed NLP models using BERT, RoBERTa, DistilBERT, spaCy, and BiLSTM-CRF architectures for text processing and classification tasks.}
\resumeItem{Built a Named Entity Recognition (NER) system to extract and structure key information from unstructured text data.}
\resumeItem{Designed text generation models using RNN and LSTM architectures, applying core NLP techniques for sequence modeling.}
\resumeItem{Implemented a Transformer model from scratch to gain a deep understanding of attention mechanisms and sequence-to-sequence architecture.}
\resumeItem{Built CNN and OpenCV-based models for a flower prediction project, enabling classification from both image and video inputs.}
\resumeItem{Developed an ANN-based digit classification model using the MNIST dataset for handwritten digit recognition.}
\resumeItem{Applied supervised and unsupervised learning techniques to build a Taxi Price Prediction model, forecasting fares based on historical trip data.}
\resumeItem{Built an end-to-end sales analytics dashboard by pushing Amazon sales data to SQL Server and visualizing key metrics using Power BI.}
\resumeItem{Performed data analysis and visualization on a Spotify dataset and huge amount of dataset using Matplotlib, NumPy, Pandas, and Seaborn to uncover trends and insights.}
\resumeItemListEnd

\resumeSubheading
{Embedded Lab Assistant}{Feb 2023 -- Sep 2023}
{IIT Delhi}{Delhi, India}
\resumeItemListStart
\resumeItem{Worked on embedded systems R\&D for 14 startups in a lab environment, assisting in the design, prototyping, and testing of hardware solutions from concept to implementation.}
\resumeItem{Designed PCB schematics using EasyEDA and performed hands-on soldering and desoldering for circuit assembly, rework, and testing.}
\resumeItem{Programmed and debugged microcontrollers using Keil and AVR Studio, converting source code into binary/hex files for embedded deployment.}
\resumeItem{Operated Universal IC Programmers to flash and upload compiled code onto microcontroller ICs for hardware testing and validation.}
\resumeItem{Assisted in designing a RISC microprocessor architecture using Cadence software, applying digital logic and processor design principles.}
\resumeItem{Developed HDL-based digital logic designs (Half Adder, logic gates) using Xilinx Vivado for FPGA-based implementation.}
\resumeItemListEnd

\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Key Projects}
\resumeSubHeadingListStart

\resumeProjectHeading{\textbf{ITSM Copilot -- Multi-Agent Ticket System}}{}
\resumeItemListStart
\resumeItem{Engineered chatbot with 5 agents and 90+ tools, managing tickets daily across different platforms.}
\resumeItem{Embedded RAG with 10,000+ historical ticket records, improving suggestion accuracy to 85\%.}
\resumeItem{Connected 100+ APIs for ticket operations, reducing average handling time from 12 minutes to 6 minutes -- a 50\% reduction.}
\resumeItem{Enabled natural language interaction for ticket management, cutting average handling time by 50\%.}
\resumeItemListEnd

\resumeProjectHeading{\textbf{Employee Productivity Analytics Chatbot}}{}
\resumeItemListStart
\resumeItem{Built analytics chatbot tracking 300+ employees across 50+ applications and 20+ projects.}
\resumeItem{Synchronized Azure DevOps with Prowatch application, analyzing 100,000+ time entries monthly.}
\resumeItem{Generated visualization dashboards, identifying productivity patterns for 15 teams.}
\resumeItem{Calculated productivity metrics with 92\% accuracy, saving managers 10 hours per week.}
\resumeItemListEnd

\resumeProjectHeading{\textbf{Code Generation Chatbot}}{}
\resumeItemListStart
\resumeItem{Created chatbot generating code in 8+ programming languages with 80--85\% accuracy on 5,000+ test cases.}
\resumeItem{Calibrated 3 Hugging Face models on 50,000+ code samples from GitHub repositories.}
\resumeItem{Processed 200+ flowchart images using OCR, achieving 78\% diagram-to-code accuracy.}
\resumeItem{Served 150+ developers, generating 10,000+ code snippets and saving 200+ development hours.}
\resumeItemListEnd

\resumeProjectHeading{\textbf{LLM Fine-Tuning \& Deployment Pipeline}}{}
\resumeItemListStart
\resumeItem{Trained 8+ models including LLaMA, Mistral, BERT, and Gemma on 200,000+ domain-specific samples and 1,000+ custom datasets.}
\resumeItem{Applied 4-bit quantization, reducing memory usage from 28GB to 7GB -- a 75\% reduction -- while maintaining 95\% performance.}
\resumeItem{Deployed FastAPI endpoints handling 500 requests per minute on AWS Lambda with 99.8\% availability.}
\resumeItemListEnd

\resumeProjectHeading{\textbf{Multi-Agent RAG System}}{}
\resumeItemListStart
\resumeItem{Constructed enterprise RAG system using LangChain and LangGraph with specialized agents for document analysis.}
\resumeItem{Incorporated ChromaDB for vector storage, achieving sub-second response times on 10,000+ documents.}
\resumeItem{Launched on AWS using Lambda and EC2 for a serverless architecture.}
\resumeItemListEnd

\resumeProjectHeading{\textbf{Database Multi-Agent Chatbot}}{}
\resumeItemListStart
\resumeItem{Designed a multi-agent Datbase system with LangGraph using Mistral and StarCoder2-7B models; a Supervisor Agent detects user intent and routes requests to either a SQL Agent or a Conversation Agent.}
\resumeItem{Set up the SQL Agent to work across 5 databases.}
\resumeItem{Tested the chatbot with 100+ users at once.}
\resumeItemListEnd

\resumeProjectHeading{\textbf{Iprovision Chatbot -- Multi-Agent Network Chatbot}}{}
\resumeItemListStart
\resumeItem{I created a multi-Agent networking chatbot user to check and manage network infrastructure such as tenants, sites, devices, and interfaces. }
\resumeItem{If the device is not reachable, it runs a Runbook to try to fix the issue automatically.}
\resumeItem{After the Runbook completes, the chatbot checks the device again. }
\resumeItem{If the device is still not reachable, the chatbot creates a ticket for this issue.}
\resumeItem{If the other agents cannot provide a solution, the chatbot uses the RAG Agent to find and provide the relevant information.}
\resumeItem{Deployed to production and validated with 200+ concurrent users, demonstrating scalability and reliability with 52 MCP tools.}
\resumeItemListEnd

\resumeSubHeadingListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
\resumeSubheading
{Deen Bandhu Chhotu Ram University of Science and Technology}{}
{Bachelor of Technology in Electronics and Communication Engineering}{July 2018 -- July 2022}
\resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
\small{\item{
\textbf{Languages}{: Python, SQL} \\
\textbf{AI/ML}{: PyTorch, TensorFlow, scikit-learn, Hugging Face, Transformers, LangChain, LangGraph, Ollama, Keras, TRL, PEFT, Bitsandbytes, Accelerate, RAG, Datasets} \\
\textbf{LLMs}{: GPT-4, Claude, Gemini, LLaMA, BERT, Mistral, Fine-Tuning (LoRA, QLoRA, PPO), Prompt Engineering} \\
\textbf{Vector DBs}{: FAISS, ChromaDB, Pinecone, PGVector} \\
\textbf{ML}{: Supervised Learning (Classification, Regression), Unsupervised Learning (Clustering, Dimensionality Reduction), Ensemble Methods (XGBoost, Random Forest, Gradient Boosting), Feature Engineering, Model Evaluation, Hyperparameter Tuning} \\
\textbf{Deep Learning}{: CNN, RNN, LSTM, Transformer Architecture, Transfer Learning, Model Optimization} \\
\textbf{NLP}{: Text Classification, Named Entity Recognition, Sentiment Analysis, Tokenization, Embeddings} \\
\textbf{MLOps}{: MLflow, Apache Kafka, Docker, Git, AWS Lambda, EC2} \\
\textbf{Cloud}{: AWS (Lambda, EC2, S3), GCP (Vertex AI)} \\
\textbf{Tools}{: FastAPI, Flask, Streamlit, Pandas, NumPy, Matplotlib}
}}
\end{itemize}

%-----------CERTIFICATIONS-----------
\section{Certifications}
\resumeSubHeadingListStart
\resumeItem{Generative AI with Amazon Web Services}
\resumeItem{Generative AI and Machine Learning}
\resumeItem{Statistics for Data Science and Business Analysis}
\resumeSubHeadingListEnd

\end{document}
