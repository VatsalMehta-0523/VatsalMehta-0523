<img src="./assets/header.svg" width="100%" alt="Vatsal Mehta. AI and full-stack developer in Ahmedabad, India. Builds multi-camera vision systems, LLM agents and RAG pipelines, and satellite change detection.">

Final-year B.E. Computer Science (AI/ML) student. I build AI products end to end: Python/FastAPI backends, React/Next.js interfaces, and the models in between, from LLM agents and RAG to vision transformers for satellite imagery.

[LinkedIn](https://www.linkedin.com/in/vatsal-mehta-/)

## Projects

### <img src="./assets/icon-anpr.svg" width="30" height="30" align="absmiddle" alt=""> [CityTraceAI](https://github.com/code-YK/ANPR-sih26) · multi-camera ANPR and traffic analytics

Links a city's ANPR cameras into one observation store, then reconstructs vehicle journeys across cameras, raises watchlist alerts and aggregates traffic analytics. Team project for Smart India Hackathon 2026 (problem statement SIH26127, Bharat Electronics Limited). I built the FastAPI backend, the PostGIS schema, the React operator console and a tool-calling LLM copilot that runs under the caller's permissions.

`Python` `FastAPI` `PostgreSQL/PostGIS` `React` `YOLO11` `ONNX Runtime` · [Demo video](https://youtu.be/L4I-Z-sIcUU)

### <img src="./assets/icon-satellite.svg" width="30" height="30" align="absmiddle" alt=""> [UrbanEye](https://github.com/VatsalMehta-0523/Satellite-Imagery-Change-Detection) · satellite change detection

Maps urban land-use change between two dates of Sentinel-2 imagery with a fine-tuned ChangeFormerV6, computes six spectral indices (NDVI, NDBI, NDWI and others), and uses a LangGraph agent to run the pipeline step by step with human approval. Related work: a SegFormer-B0 fine-tuned on DeepGlobe for an ISRO road-extraction problem.

`PyTorch` `ChangeFormer` `Sentinel-2` `LangGraph` `FastAPI` `React` · [Demo video](https://youtu.be/ce8-K_piZhI)

### <img src="./assets/icon-memory.svg" width="30" height="30" align="absmiddle" alt=""> [NeuroHack](https://github.com/VatsalMehta-0523/NeuroHack) · long-term memory for conversational AI

Extracts facts, preferences and commitments from a conversation, stores them, and retrieves only the relevant ones into the context window on later turns. Memories decay with time and disuse. Rank 24 of 800+ teams at NeuroHack 2026 (IIT Guwahati).

`Python` `PostgreSQL (pgvector)` `Embeddings` `Streamlit` · [Live demo](https://neurohack.streamlit.app/)

### <img src="./assets/icon-shield.svg" width="30" height="30" align="absmiddle" alt=""> [Security-Copilot](https://github.com/vedant-kalal/Security-Copilot) · agentic email and URL threat detection

A LangGraph agent that investigates an email or URL: origin trace, SPF/DKIM/DMARC checks, sandboxed links and attachments, and a risk-scored verdict, surfaced through a Gmail add-on and a Chrome extension. Team project, 1st place at Maveric Effect 2026.

`LangGraph` `BERT` `ONNX` `FastAPI` `Next.js` · [Demo video](https://youtu.be/amZM1H0NQ84)

### <img src="./assets/icon-bell.svg" width="30" height="30" align="absmiddle" alt=""> [Meet Attendance Tracker](https://github.com/VatsalMehta-0523/meet-attendance-tracker) · published Chrome extension

My college takes surprise attendance on Google Meet, so I built an extension that catches it. It reads Meet captions and chat on-device, never audio, detects a roll call and sounds an alarm. Used by classmates.

`JavaScript` `Chrome Extension (Manifest V3)` · [Chrome Web Store](https://chromewebstore.google.com/detail/meet-attendance-tracker/hgjmfjempcmmbiipppmmkmoifehbpacb)

### Smaller projects

- **[ParkSmart](https://github.com/VatsalMehta-0523/parking-system)**: parking management for providers, with YOLO-based slot occupancy monitoring, bookings and analytics. FastAPI, PostgreSQL, React.
- **[Smart Farm](https://github.com/VatsalMehta-0523/smart-farm)**: visitors scan a plant's QR code to explore a botanical farm; admins manage the content. Next.js, Supabase. [Live site](https://smart-farm-tau-six.vercel.app)

## Background

- B.E. Computer Science Engineering (AI/ML), New L.J. Institute of Engineering and Technology (GTU), 2023 to 2027. CGPA 9.68/10.
- AI/ML Intern at Meru Technosoft, May to August 2026: a tool-calling LLM chatbot on FastMCP, document-extraction pipelines, and API integrations.
- Three hackathon placements: two first places and one runner-up.
- NPTEL Deep Learning: 100/100, Elite + Gold.

## Stack

**Languages and web:** Python, SQL, JavaScript, React, Next.js<br>
**Machine learning:** PyTorch, Hugging Face Transformers, scikit-learn, OpenCV<br>
**LLMs and agents:** RAG, embeddings, vector databases, tool calling, LangGraph<br>
**Backend and cloud:** FastAPI, PostgreSQL/PostGIS, Google Cloud
