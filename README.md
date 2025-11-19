# AI CUSTOM RAG AGENT CHATBOT
## Automated Document Q&A Agent For Instant Chat-based Knowledge Access

## Project Overview
This project is a Retrieval-Augmented Generation (RAG) workflow built in **n8n**. It uses **Telegram** for chat interaction, **Supabase** for vector search, **PostgreSQL** for agent memory, and **Google Drive** for document ingestion.

# 🧠 Telegram RAG Agent with Supabase & PostgreSQL (via n8n)

This project is a Retrieval-Augmented Generation (RAG) workflow built in **n8n**. It uses **Telegram** for chat interaction, **Supabase** for vector search, **PostgreSQL** for agent memory, and **Google Drive** for document ingestion.

---

## Real-Life Case Study

### 📚 Internal Knowledge Bot for HR Teams

**Problem**  
Many HR teams store policies, onboarding packs, and compliance documents across Google Drive. Staff often ask the same questions repeatedly, which slows down the team.

**Solution**  
This workflow lets HR upload documents into Google Drive and have them automatically embedded into Supabase. Team members can message a Telegram bot to ask questions, and the bot pulls answers directly from the stored documents.

---

## How It Works

1. **Upload** a document to a Google Drive folder.  
2. n8n **extracts**, **embeds**, and **stores** the text in Supabase.  
3. Metadata and memory go to **PostgreSQL**.  
4. A user asks a question in **Telegram**.  
5. The workflow retrieves relevant content and sends an answer back.

---

## Where This Is Useful

- HR and internal policy assistants  
- Legal and compliance teams  
- Customer support knowledge lookup  
- Healthcare SOP reference  
- Education and training material assistants  

---

## Stack

- n8n  
- Telegram Bot API  
- Google Drive  
- Supabase (pgvector)  
- PostgreSQL  
- Any embedding model supported by your setup  

---

## Project Structure

