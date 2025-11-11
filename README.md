# 👋 Hi, I’m Rahul Sharma

AI/ML engineer with **5 yrs in industry** shipping production systems — LLMs, vision models, and ML pipelines that *actually* get used.

- 🎓 MS Data Science @ UMD (4.0)
- 🩺 Recently deep in **medical AI**: offline RAG, radiology VLMs, label ensembles, and cloud imaging infra
- 🛠 I turn messy data + business goals into shipped features with metrics, monitoring, and CI/CD

---

## 🔎 Recent Work (selected)

- **Emotion-Aware NPCs (real-time CV for games)** — webcam-based system that senses a player’s affect and adapts NPC dialogue in a Unity game in real time. Uses facial emotion recognition plus valence–arousal mapping, temporal smoothing, and multi-signal fusion (FER + eye aspect ratio, head pose, optical flow) with a FastAPI backend.  
  _Stack:_ Python · FastAPI · ONNX FER models · temporal emotion dynamics (EMA, spike detection) · Unity 2022 (C# client) · REST API integration  
  **Code:** https://github.com/rahul370139/EmotionAwareNPCs

- **MARCH-PAWS Offline RAG Assistant (medical)** — reads TCCC-style medical manuals and produces grounded, step-by-step **MARCH-PAWS** checklists using a finite-state orchestrator and hybrid retrieval. Designed to run fully offline on a laptop once indexes are built.  
  _Stack:_ Python · Streamlit · BM25 + FAISS + **Reciprocal Rank Fusion** · cross-encoder re-ranking · asyncio + ThreadPool · Ollama (Mistral-7B)  
  **Code:** https://github.com/rahul370139/marchpaws_rag

- **MIMIC-CXR Radiology Report Generation** — fine-tuned **LLaVA-NeXT v1.6-Mistral-7B** with LoRA on A100 to generate structured JSON radiology reports from chest X-rays, with optional EHR conditioning and A/B testing (image vs image+EHR). Includes multi-pass JSON-first prompting and an interactive Streamlit demo.  
  _Stack:_ LLaVA-NeXT v1.6 · LoRA · bf16 training · curriculum learning (Image→Impression, Image+EHR→Reasoning/ICD) · Streamlit · JSON-structured output  
  **Code:** https://github.com/rahul370139/radiology_report

- **CheXpert Label Ensemble (CheXagent + TorchXRayVision)** — ensemble pipeline for **CheXpert** labels combining TorchXRayVision DenseNet probabilities with CheXagent reasoning, plus per-label calibration and threshold tuning for precision-first medical setups.  
  _Stack:_ TorchXRayVision · CheXagent · Platt scaling · F-beta optimization · per-label logistic-regression blending · precision-gating utilities  
  **Code:** https://github.com/rahul370139/chexpert_labels

- **doc2data — Document-to-Data Pipeline** — production-ready **PDF/image → JSON** pipeline: layout segmentation, OCR, semantic labeling stubs, and a Streamlit UI with threshold controls. CPU-friendly today, GPU-ready, with FastAPI endpoints for integration.  
  _Stack:_ LayoutParser (PubLayNet, TableBank) · PaddleOCR + Tesseract · heuristic layout rules · Streamlit · FastAPI · Docker · modular pipelines  
  **Code:** https://github.com/rahul370139/doc2data

- **RadStream — Cloud-Native Medical Imaging Pipeline** — AWS-first design for streaming medical images through serverless ingestion, EKS/Triton inference, and full telemetry into a data lake for analytics. Focused on latency, observability, and security vs traditional PACS.  
  _Stack:_ AWS Lambda · Step Functions · EventBridge · EKS + NVIDIA Triton · Kinesis · S3 · Glue · Athena · QuickSight · IAM/WAF/GuardDuty  
  **Code:** https://github.com/rahul370139/Radstream

- **SkillSpring** — PDF → microlearning (summaries, flashcards, quizzes), chatbot with framework detection, and career-path suggestions.  
  _Stack:_ FastAPI · LangChain/LangGraph · Cohere · Supabase/pgvector · Next.js · Tailwind · shadcn/ui · Vercel/Railway  
  **Demo:** https://skillspring001.vercel.app/ · **Code:** https://github.com/rahul370139/SkillSpring

- **Multimodal Fashion RecSys** — CLIP-based similarity + FAISS retrieval with captioning and segmentation to boost text–image match; supports virtual wardrobe and outfit recommendations.  
  _Stack:_ CLIP embeddings · BLIP captioning · segmentation models · FAISS · Streamlit demo  
  **Code:** https://github.com/rahul370139/Fashion_Recommendation_model_demo

---

## ⚙️ Tech I Love (toolbox)

**Languages/Runtime:** Python, SQL  
**Backend & Apps:** FastAPI, REST APIs, async workers, Streamlit apps

**Orchestration & Agents:** LangGraph, LangChain, async finite-state machines, MCP (Model Context Protocol), tool/function-calling  

**Retrieval & Data:** BM25, FAISS, **Reciprocal Rank Fusion**, pgvector/Supabase, Chroma, document pipelines, data quality checks  

**LLM & Vision Ops:** RAG systems (online + offline), prompt design, VLMs (LLaVA-NeXT, CLIP), evaluation (Langfuse, RAGAS), guardrails, JSON-first interfaces  

**Medical Imaging Stack:** TorchXRayVision, CheXagent, chest X-ray classification, label calibration & threshold tuning, report generation  

**Cloud & Infra:** AWS (Lambda, Step Functions, EventBridge, EKS, Kinesis, S3, Glue, Athena, QuickSight), Docker, GitHub Actions, Vercel, Railway  

**Automation (no/low-code):** Make, n8n, webhooks, API integrations

---

## 🧩 Problem Areas I’m Good At

- **Medical AI:** radiology VLMs, CheXpert label ensembles, protocol-driven checklists (MARCH-PAWS), imaging pipelines  
- **Affective & game AI:** real-time emotion-aware NPCs, webcam-CV → gameplay adaptation  
- **Document intelligence:** layout/OCR pipelines, PDF → JSON, doc-grounded RAG, workflow automation  
- **Computer vision:** chest X-rays, medical imaging, real-time CV pipelines  
- **Time series forecasting & monitoring**  
- **NLP/NLU:** topic discovery, anomaly detection, fine-tuning, retrieval-augmented systems  
- **Recommendation systems:** multimodal embeddings, similarity search, re-ranking  
- **Automation/orchestration:** async workflows, evaluators, CI-ready ML pipelines

---

## 🧪 Exploring Now

Offline / edge-friendly RAG · safer medical assistants with strong refusal + grounding · agentic workflows with verifiable tool calls · structured outputs (Pydantic/JSON Schema) · eval-first pipelines for both LLM and vision-language models

---

## 🔗 Links

**Portfolio:** https://rahul370139.github.io/git_portfolio/  
**GitHub:** https://github.com/rahul370139  
**LinkedIn:** https://www.linkedin.com/in/rahul-sharma--/
