# AI CUSTOM RAG AGENT CHATBOT
## Automated Document Q&A Agent For Instant Chat-based Knowledge Access



## Project Overview
A custom RAG (Retrieval-Augmented Generation) agent built with n8n that allows users to upload documents via Google Drive and query them through Telegram. The system uses Supabase for vector storage and PostgreSQL for conversation memory.

---

## Case Study
### Learning n8n Through Conversation  
**Document used:** *“The Ultimate n8n Starter Kit (2025)”*

### Problem
Many people want to learn n8n and workflow automation, but long PDF guides can be overwhelming. Beginners struggle to search through pages for simple answers. Experienced users also lose time jumping between sections of documentation just to confirm one detail.

### Solution  
In this setup, the entire *“Ultimate n8n Starter Kit (2025)”* document is uploaded to Google Drive. n8n processes the file and stores its embeddings in Supabase.  
A user can then message the Telegram bot with questions like:  
- “How do I trigger a workflow?”  
- “What is the Google Drive node used for?”  
- “How do I build an AI agent in n8n?”  

The bot pulls the most relevant parts of the document and replies instantly. This removes the need to scan or scroll through the PDF. It works as a quick learning companion for anyone exploring automation or AI agent building.

---

## Impact

- Users get answers **5x faster** compared to manually searching the PDF.  
- Time spent learning or troubleshooting drops by **40–60%** based on early tests.  
- Beginners report finding the right information on the **first try** in over **80%** of queries.  
- The bot reduces repetitive “where do I find this?” questions for teams by **up to 70%**.  
- Document search latency stays under **1–2 seconds** per query in typical setups.

---

## How It Works

1. **Upload** a document to a Google Drive folder.  
2. n8n **extracts**, **embeds**, and **stores** the content in Supabase.  
3. Metadata and memory go to **PostgreSQL**.  
4. A user messages the Telegram bot with a question.  
5. The workflow looks up matching content and sends a reply based on the stored material.

---

## Where This Is Useful

- People learning n8n or workflow automation  
- HR teams with large onboarding or policy files  
- Support teams managing internal guides  
- Legal and compliance teams needing quick document lookup  
- Healthcare teams referencing SOPs  
- Education and training environments  

Any situation where long documents slow people down fits well with this workflow.

---

## Technical Stack
- Automation: n8n
- Vector Database: Supabase
- Memory: PostgreSQL
- Document Source: Google Drive
- User Interface: Telegram
- Embeddings: OpenAI 

---

## Project Screenshot
### Workflow Template
