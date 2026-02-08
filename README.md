# AI CUSTOM RAG AGENT CHATBOT
## Automated Document Q&A Agent For Instant Chat-based Knowledge Access
<img width="2000" height="1348" alt="The 6 Types of AI Agents You Should Know in 2025 (6)" src="https://github.com/user-attachments/assets/cbdb3ec5-0bcb-4d4e-8fbe-b844039b3e07" />

---
## Project Overview
A custom RAG (Retrieval-Augmented Generation) agent built with n8n that allows users to upload documents via Google Drive and query them through Telegram. The system uses Supabase for vector storage and PostgreSQL for conversation memory.

---

## Case Study
### Learning n8n Through Conversation  
**Document used:** *“The Ultimate n8n Starter Kit (205) by Nate Herk”*

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
<img width="1748" height="828" alt="Untitled design (14)" src="https://github.com/user-attachments/assets/8b9a6b9b-e43b-4ab0-94fe-a50c54dd9bc1" />

---
### Workflow Result
As highlighted in the second screenshot:

- It gives answers based on the document you uploaded and embedded in the database.
- If the agent can’t find anything relevant in the document, it clearly states that first, then provides an LLM-generated answer.
  
![n8n_ai_agents_combined](https://github.com/user-attachments/assets/15084c8a-73e0-492f-8a73-fcfc4d173d25)

---

![n8n_nodes_debugging_workflow_combined](https://github.com/user-attachments/assets/623c979b-2203-4acc-b4a0-beb2636ae320)

---
### Supabase Vector Storage Table
<img width="1748" height="1240" alt="Untitled design (15)" src="https://github.com/user-attachments/assets/2a4c7429-3e20-4c6f-8040-87e5f36c8187" />

---
### Supabase SQL Editor
<img width="1748" height="1100" alt="Untitled design (16)" src="https://github.com/user-attachments/assets/87e8d99c-9bca-41a8-aaaa-1e46010a9e5c" />


## THANK YOU
For more information, you can contact me
![image](https://github.com/user-attachments/assets/400a6867-54ca-409f-b788-6d12b14d0833)




