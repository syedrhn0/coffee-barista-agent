# ☕ Coffee Barista Agent

A RAG-powered AI Barista built with Google ADK, Gemini, Streamlit, and deployed on Cloud Run.
Includes an optional Firestore + Vector Search upgrade for live menu grounding.

## Live demo
https://coffee-barista-xxxxx.a.run.app  <!-- replace with your actual URL -->

## Features
- Custom ADK `LlmAgent` with a `get_menu()` tool
- Streamlit chat UI with session state
- Deployed via Cloud Run source-based builds
- Optional: Firestore vector search for dynamic menu grounding