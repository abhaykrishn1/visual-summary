 Video Summarization Tool using Local LLM

Summarize videos visually and textually using key frames and a local LLM Gemma 3 Upload any video and get a short AIgenerated summary with frame highlights

 Features:
 Extracts key frames from videos
 Uses Gemma 3 via Ollama for local LLM summaries. (can use any Multi modal LLM/API calls for same)
 Simple Streamlit web interface

 Quick Start:
1. Install Ollama  Gemma 3
   bash
   ollama pull gemma3:27b

2 Install dependencies
   bash
   pip install -r requirements.txt

3 Run the app
   bash
   streamlit run video_summary.py

 Usage:
 Upload a video file in the app
 View the key frames and the generated summary