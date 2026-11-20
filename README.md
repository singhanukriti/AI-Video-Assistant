# AI-Video-Assistant

A multimodal video understanding system that enables semantic search, question answering, timeline generation, highlights extraction, and visual search over uploaded videos.

## Features

* **Video Upload:** Upload local video files for automated multimodal processing.
* **YouTube Import:** Directly import and analyze videos via YouTube links.
* **Whisper Transcription:** Accurate speech-to-text transcription powered by Whisper.
* **Semantic Transcript Search:** Search across spoken content using natural language queries.
* **Question Answering (RAG):** Ask complex questions and get context-aware answers grounded in the video content.
* **Timeline Generation:** Automatically generate structured, timestamped video timelines.
* **AI Highlights:** Extract key moments and highlights from long-form videos.
* **Visual Search using BLIP:** Search video frames visually using natural language descriptions.
* **FastAPI Backend:** High-performance, asynchronous Python API.
* **React Frontend:** Modern, responsive, and interactive user interface.

## Tech Stack

### Backend
* **Framework:** FastAPI
* **Transcription:** Whisper
* **Vector Search:** FAISS
* **Embeddings & Vision:** Sentence Transformers, BLIP
* **LLM:** OpenAI

### Frontend
* **Framework:** React
* **HTTP Client:** Axios
* **Animations:** Framer Motion
* **Routing:** React Router

## Getting Started

### Run Backend

1. Navigate to the backend directory:
   ```bash
   cd multimodal-qa-agent
   ```
2. Activate your virtual environment:
   ```bash
   venv\Scripts\activate      # Windows
   # source venv/bin/activate # Mac/Linux
   ```
3. Start the FastAPI server:
   ```bash
   uvicorn api.app:app --reload
   ```

### Run Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Future Improvements

* **OCR Search:** Extract and index on-screen text from video frames.
* **Clip Extraction:** Export and download specific video segments directly from search results.
* **Cross-Video Search:** Query across an entire library of uploaded videos simultaneously.
* **Object Detection:** Identify and track specific objects across video timelines.
* **Video Chapters:** Automatically segment videos into titled chapters.
* <img width="1896" height="968" alt="image" src="https://github.com/user-attachments/assets/79c4d926-be14-4685-94fb-78fb9ca97e66" />
<img width="1806" height="878" alt="image" src="https://github.com/user-attachments/assets/75994a20-e9d6-4f9a-87d0-214108d2b904" />
<img width="1918" height="1023" alt="image" src="https://github.com/user-attachments/assets/775363a6-3aa1-46ad-90c8-8c1d46545f52" />
<img width="1393" height="904" alt="image" src="https://github.com/user-attachments/assets/2591d694-601a-4c10-a871-4d9b889a9e07" />
<img width="1201" height="745" alt="image" src="https://github.com/user-attachments/assets/4420ba69-4898-488c-8f5d-9396df350cf2" />
<img width="1046" height="252" alt="image" src="https://github.com/user-attachments/assets/bd13bf0b-f6b2-4287-9196-a7957c765c04" />



