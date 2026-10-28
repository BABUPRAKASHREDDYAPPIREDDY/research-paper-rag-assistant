# Research Paper RAG Assistant

### A Retrieval-Augmented Question-Answering and Literature Support System for Academic Papers

## 📌 Overview

The Research Paper RAG Assistant is a proposed AI-based application designed to help students and researchers interact with academic research papers more efficiently.

The project aims to use **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from uploaded research papers and generate answers based on the retrieved content.

## 🎯 Problem Statement

Students and researchers often need to read multiple research papers to understand a topic, compare methodologies, identify datasets, and analyse findings. Manually searching through lengthy documents can be time-consuming.

General-purpose AI tools may also provide answers that are not directly supported by the papers being studied.

This project proposes a system that allows users to ask questions about their research papers and receive answers grounded in the uploaded documents, with relevant source references.

## 🎯 Objectives

* Understand the fundamentals of Retrieval-Augmented Generation.
* Extract and process text from academic research papers.
* Divide documents into manageable text chunks.
* Generate embeddings and store them for efficient retrieval.
* Retrieve relevant information based on user queries.
* Generate answers supported by the retrieved passages.
* Develop a simple interface for uploading papers and asking questions.
* Evaluate the accuracy and usefulness of the system.

## ⚙️ Proposed System Workflow

The proposed system is expected to follow these stages:

1. **Document Upload:** Upload academic papers in PDF format.
2. **Text Extraction:** Extract text from the uploaded documents.
3. **Text Chunking:** Divide the extracted text into smaller sections.
4. **Embedding Generation:** Convert text chunks into numerical representations.
5. **Vector Storage:** Store the embeddings in a vector database.
6. **Information Retrieval:** Retrieve relevant passages based on the user's question.
7. **Answer Generation:** Use a language model to generate an answer grounded in the retrieved content.
8. **Source References:** Display relevant source information alongside the answer.

## 🛠️ Proposed Technologies

The final technology stack has not yet been decided. The following tools are being considered for exploration:

| Component            | Possible Technologies           |
| -------------------- | ------------------------------- |
| Programming Language | Python                          |
| PDF Text Extraction  | PyMuPDF, pdfplumber             |
| RAG Framework        | LangChain, LlamaIndex           |
| Embedding Models     | Sentence Transformers           |
| Vector Database      | FAISS, ChromaDB                 |
| Language Model       | API-based or locally hosted LLM |
| User Interface       | Streamlit, Gradio               |
| Version Control      | Git, GitHub                     |

## 🚀 Planned Features

* Question answering based on uploaded research papers.
* Answers supported by relevant source references.
* Summarisation of research papers.
* Comparison of multiple papers.
* Extraction of key information, such as methods, datasets, results, and limitations.

These features are proposed and may be adjusted according to the project's feasibility and progress.

##  Project Scope

The initial focus will be on developing a basic question-answering system for a small collection of research papers.

Advanced features and evaluation experiments will be considered after the basic system is functional.

##  Current Project Status

**Stage:** Initial idea selection and exploration.

The project topic has been selected, and a preliminary system blueprint has been explored. Detailed literature review, technology selection, implementation, and testing are yet to be completed.

##  Team

This is a two-member team project being undertaken as part of the PRISM course.

Individual responsibilities and contributions will be documented as the project progresses.

##  Future Improvements

Potential future improvements include:

* Hybrid keyword and semantic retrieval.
* Improved citation accuracy.
* More reliable handling of scientific documents.
* Better comparison of research papers.
* Evaluation of different retrieval and embedding approaches.

##  Note

This README describes the proposed project. The technologies, features, and implementation details may change as the team progresses through research and development.
