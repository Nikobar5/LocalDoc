# LocalDoc

**AI-Powered Document Intelligence for Your Desktop**

---

## Overview

LocalDoc is a desktop application that lets you leverage local and cloud AI models for smart document analysis. Easily upload, process, and search your documents—PDFs, Word, PowerPoint, Excel, CSV, TXT, and JSON—and get context-aware AI assistance. All processing happens directly on your device, ensuring your workflow remains fast and flexible.

---

## Key Features

### 📄 Universal Document Upload

- Supports PDF, DOCX, PPTX, XLSX, CSV, TXT, JSON
- Drag and drop for bulk uploads

### 🧐 Semantic Search & Embedding

- Processed documents are embedded into a vector database (ChromaDB)
- Enables semantic search and question answering grounded in your uploaded materials

### 📋 Automatic Summarization

- Summarizes documents using local language models
- Quick insight into document content

### ⚡ Fast Local Processing

- Leverages Ollama for running popular open-source language models locally
- No mandatory cloud dependency for document search or summarization

---

## Technology Stack

- **Frontend:** React, TypeScript, TailwindCSS (with Vite)
- **Desktop Framework:** Electron (cross-platform support for Windows, macOS, Linux)
- **Backend:** Python (LangChain for orchestration)
- **Local AI Models:** via Ollama (LLaMA 3, Mistral, etc.)
- **Semantic Search:** ChromaDB
- **Document Parsing:** Supports PDF, DOCX, PPTX, XLSX, CSV, TXT, JSON
- **Other Libraries:** Openpyxl, python-pptx, python-docx, FPDF

---

## Example Workflow

1. **Launch Herma on your Desktop**
2. **Upload Documents** (drag-n-drop or file picker)
3. **Process & Summarize**—Herma parses and summarizes documents automatically
4. **Semantic Search**—Ask questions about your documents, and get context-aware answers

---

## Supported File Types

- PDF (.pdf)
- Word (.docx)
- PowerPoint (.pptx)
- Excel (.xlsx)
- CSV (.csv)
- Plain Text (.txt)
- Markdown (.md)
- JSON (.json)

---
