# AI-Powered Meeting Summarization Assistant  

The **AI-Powered Meeting Summarization Assistant** is an end-to-end system that transforms meeting audio and transcripts into concise, structured summaries. By leveraging state-of-the-art AI models and a Retrieval-Augmented Generation (RAG) pipeline, the system significantly reduces review time and enhances organizational productivity through real-time, context-aware outputs.  

---

## Key Contributions  
- **70% reduction** in meeting review time across **60+ hours of transcripts**  
- Achieved **80%+ summarization accuracy** using a chunk-based RAG pipeline  
- Designed and deployed a full-stack solution integrating:  
  - **Whisper** for transcription  
  - **GPT-4** for summarization and action item extraction  
  - **FastAPI** for backend orchestration  
  - **React** for an intuitive user interface  

---

## System Overview  
1. **Transcription** – Audio inputs are transcribed into text via Whisper  
2. **Chunking & Retrieval** – Transcripts are segmented into context-rich chunks, retrieved dynamically for processing  
3. **Summarization** – GPT-4 generates concise summaries, highlighting key decisions and action items  
4. **Backend Services** – FastAPI handles API routing and manages the processing pipeline  
5. **Frontend Interface** – React-based dashboard enables file upload, real-time viewing, and export of summaries  

---

## Technology Stack  
- **AI Models**: Whisper, GPT-4  
- **Backend**: FastAPI (Python)  
- **Frontend**: React.js  
- **Pipeline**: Retrieval-Augmented Generation (RAG)  
- **Infrastructure & Tools**: Docker, REST APIs  

---

## Example Output  

**Transcript Excerpt:**  
> “We need to finalize the project timeline by next week and assign tasks for frontend and backend development.”  

**Generated Summary:**  
- Finalize project timeline by next week  
- Assign tasks for frontend and backend development  

---

## Impact  
- Cuts down **hours of manual review** to **minutes**, boosting efficiency  
- Provides **structured knowledge capture**, improving collaboration across teams  
- Scales seamlessly to handle **large volumes of organizational transcripts**  

---

## Getting Started  

### Backend Setup  
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

Frontend Setup
cd frontend
npm install
npm start
