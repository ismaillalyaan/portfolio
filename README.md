# Ismail Elyan — Portfolio

Single-page personal portfolio site. Static HTML/CSS/JS, no build step, no framework.

**Live:** deployed via GitHub Pages from this repo.

## What's here

- `index.html` — the entire site (sidebar nav, about, experience, skills, projects, certifications, education)
- `photo.png` — profile photo
- `proj_advisor.png`, `proj_nestora.png`, `proj_admission.png` — project card images
- `ai pracioner.png`, `cloud_practionoer.webp`, `ml_associate.png`, `solutions architect.png` — AWS certification badges
- `Ismail Elyan - Ai Enigneer.pdf` — downloadable CV (linked from the sidebar's "Download CV" button)

## Featured projects

1. **AI-Powered Academic Advisor Chatbot** — LangGraph ReAct agent, Neo4j knowledge graph, Pinecone RAG, Supabase.
2. **Nestora** — Flutter app + FastAPI backend that turns a room floor plan into an AI-furnished 2D CAD layout (Groq vision/LLM, OpenCV).
3. **BNU Admission Chatbot** — bilingual (AR/EN) RAG assistant with hybrid Pinecone + BM25 retrieval and automatic Google Drive ingestion.

## Editing

No build tools — open `index.html` directly in a browser to preview, or serve the folder statically. All styling is inline `<style>` in the same file (CSS custom properties at the top under `:root` for colors/fonts/spacing).

To update the CV, replace `Ismail Elyan - Ai Enigneer.pdf` (filename must match the download link in the sidebar).
