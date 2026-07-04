<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  Abdullah Khan (AI Engineer) · Profile README                ║
  ║  Hero: Toptal brand palette (#204ECF on deep navy).          ║
  ║  Body: CV styling - black text, white page, bold uppercase   ║
  ║  headers. Content verbatim from the CV.                      ║
  ║  ▸ Replace  YOUR_LINKEDIN  with your LinkedIn slug            ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<!-- ░░░ HERO - Toptal brand palette: deep navy to Toptal blue ░░░ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0A1B4D,55:1B3FA8,100:204ECF&height=210&section=header&text=Abdullah%20Khan%20(AI%20Engineer)&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Toptal-Vetted%20%C2%B7%20Top%203%25%20of%20Global%20Engineering%20Talent&descSize=17&descAlignY=58&animation=fadeIn" alt="banner"/>

<!-- ░░░ TYPING ANIMATION - Toptal blue ░░░ -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Georgia&weight=600&size=18&pause=1200&color=FFFFFF&center=true&vCenter=true&width=950&height=60&lines=Delivering+ROI-driven+AI+solutions+from+proof+of+concept+to+production;Architecting+RAG+pipelines+and+multi-agent+systems+at+enterprise+scale;Serving+Healthcare%2C+Finance+and+E-commerce+clients;Across+the+UK%2C+North+American+and+UAE+markets" alt="Typing SVG"/>
</a>

<!-- ░░░ LINKS - original-color brand logos, clickable ░░░ -->
<p>
  <a href="https://www.linkedin.com/in/abdullah-khan-590545313" title="LinkedIn">
    <img src="https://img.icons8.com/color/96/linkedin.png" width="44" height="44" alt="LinkedIn"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/abdullah-khan-aie" title="GitHub">
    <img src="https://cdn.simpleicons.org/github/181717/ffffff" width="44" height="44" alt="GitHub"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://www.toptal.com/developers/resume/abdullah-khan" title="Toptal, Top 3% of Global Talent">
    <img src="https://cdn.simpleicons.org/toptal" width="44" height="44" alt="Toptal"/>
  </a>
  &nbsp;&nbsp;
  <a href="mailto:abdullah_khan.dev@proton.me" title="Email">
    <img src="https://cdn.simpleicons.org/protonmail" width="44" height="44" alt="Email"/>
  </a>
</p>

<!-- ░░░ TOPTAL - TOP 3% ░░░ -->
<a href="https://www.toptal.com/developers/resume/abdullah-khan">
  <img src="https://readme-typing-svg.demolab.com?font=Georgia&weight=700&size=16&duration=4000&pause=900&color=FFFFFF&center=true&vCenter=true&width=850&height=50&lines=Toptal-vetted+AI+Engineer%2C+ranked+among+the+top+3%25+of+global+engineering+talent" alt="Toptal, Top 3% of Global Talent"/>
</a>

<sub>Accepted into the <a href="https://www.toptal.com/developers/resume/abdullah-khan">Toptal network</a> after completing its rigorous, multi-stage screening process, an evaluation of technical depth, communication, and professionalism that fewer than 3% of applicants pass. <a href="https://www.toptal.com/developers/resume/abdullah-khan">View my verified Toptal résumé →</a></sub>

</div>

---

## PROFILE

- AI Engineer and Data Scientist with the expertise on delivering ROI-driven solutions.
- Transformed raw data into revenue-generating insights, helping clients dominate their markets.
- Expertise in developing end-to-end Data Products, from conceptualisation, proof of concept – POC, to full scale production, with a focus on Healthcare, Finance, and e-com sectors in the UK, North American and UAE markets.

---

## PROFESSIONAL EXPERIENCE

### AI Engineer: Devsinc <sub>Dec 2025 – Present</sub>

Architected and scaled a modular AI Agent Orchestration Platform designed to automate complex B2B workflows, reducing operational overhead by 40% and enabling enterprise clients to deploy custom autonomous agents at scale.

- Designed a high-performance RAG (Retrieval-Augmented Generation) Pipeline utilising Python (FastAPI) and Vector Databases (Pinecone/Weaviate). Implemented advanced retrieval strategies including hybrid search (semantic + keyword), re-ranking models (Cohere), and query expansion to ensure 95%+ accuracy in context retrieval for domain-specific knowledge bases.
- Engineered a Multi-Agent Workflow Engine using LangGraph and CrewAI, enabling collaborative task execution between specialised agents. Implemented state management and "Long-term Memory" modules using Redis, allowing agents to maintain context across multi-session user interactions.
- Optimised LLM Inference and Cost Management by implementing a dynamic routing layer that selects models (GPT-4o, Claude 3.5 Sonnet, or Llama 3) based on task complexity and token cost. Developed a custom Semantic Caching layer that reduced API latency by 60% for repetitive queries.
- Built a "Human-in-the-Loop" (HITL) Intervention UI, integrating with Slack and Microsoft Teams. The system pushes high-uncertainty agent decisions to human supervisors for real-time correction, using the feedback to fine-tune local models and improve future autonomous performance.
- Implemented Full-Stack Observability and evaluation frameworks using LangSmith and Weights & Biases. Established automated "eval" suites to test for hallucinations, prompt injections, and regression across model updates, ensuring production-grade reliability for enterprise deployments.
- Developed and Deployed Scalable Infrastructure on AWS (EKS, Lambda, SQS) using Terraform (IaC). Leveraged Docker and Kubernetes to manage auto-scaling GPU workloads for local model fine-tuning (LoRA/QLoRA) and high-concurrency inference tasks.
- Integrated Complex Data Connectors, building asynchronous ETL pipelines to ingest and structure unstructured data from various sources (Google Drive, Notion, PostgreSQL, and Zendesk), transforming them into searchable embeddings for the RAG engine.

### AI Engineer: Prypco <sub>Oct 2023 – Nov 2025</sub>

Architected and deployed an end-to-end AI Document Intelligence Platform for mortgage processing, reducing manual data entry and enabling real-time validation feedback loops between Mortgage Advisors (MAs) and customers.

- Designed a high-performance, asynchronous validation engine using Python (FastAPI) and Azure Document Intelligence (OCR) to process complex financial documents (Passports, Bank Statements, Salary Certificates). Implemented structured data extraction using OpenAI (GPT-5.2) with strict Pydantic schema validation to ensure data integrity.
- Engineered a multi-channel orchestration layer integrating WhatsApp and Slack. Built a "Human-in-the-Loop" workflow where:
  - Customers are onboarded and nudged via WhatsApp to upload documents.
  - AI extraction results and validation issues are pushed instantly to Slack threads for MA review.
  - MA verdicts (Approve/Reject) trigger automated feedback to the customer portal, streamlining the re-upload process for rejected documents.
- Implemented complex domain logic and cross-document validation, enabling the system to automatically detect inconsistencies across file sets (e.g., matching salary credits in bank statements against salary certificates, verifying residency status across Visa/Passport/EID) before the case reaches the Credit Analyst.
- Integrated full-stack observability using Langfuse, creating a granular tracing system that tracks the lifecycle of every document. Developed custom dashboards to monitor:
  - AI vs. Human Agreement: Tracking how often MAs override AI verdicts.
  - Operational Metrics: Latency, total pipeline cost per application, and document rejection rates.
- Optimised infrastructure cost and performance by implementing a non-blocking architecture (asyncio) for I/O-bound tasks and thread-pooling for CPU-bound OCR tasks, ensuring the system handles high-concurrency workloads without degradation.

### Data Scientist: SutureHealth <sub>Jan 2021 – Aug 2023</sub>

- Designed and implemented a patient-facing care plan generation app, enabling end-to-end workflows from mobile audio recording (between physician and patient) to structured care plan output.
- Built and evaluated a multi-model transcription pipeline (AWS Transcribe, HealthScribe, AssemblyAI, Deep-gram Nova3, Medical Transcribe), selecting optimal services for MVP. Implemented two transcription flows:
  - Batch transcription for downstream NLP AI agent summarisation and structured care plan generation.
  - Live transcription via WebSockets, incorporating chunking and latency optimisation for near real-time closed captioning.
- Developed an agent-based orchestration layer that summarises doctor-patient conversations into predefined structured encounter notes.
- Architected and deployed backend infrastructure using AWS ECS Fargate, Kinesis, Lambda, SQS, S3, RDS, SNS, Cognito, IAM, and Terraform/CDK for HIPAA-compliant scalability.
- Implemented OCR workflows with AWS Textract for extracting structured data from clinical documents.
- Delivered a solution for another client to classify medical documents, extract key metadata, and detect bounding boxes for physician signatures and dates, leveraging LLM agents + AWS Textract.

---

## SKILLS

**Computer Vision & Real-Time Systems:** Object Detection (YOLOv5, Faster R-CNN), Image Segmentation, OCR, Edge Computing, Video Frame Analysis, Visual Inspection, IoT Integration (Arduino, ESP, Raspberry Pi)

**AI/ML Algorithms:** Reinforcement Learning, Zeroshot & Few-shot Learning, Gradient Boosting, Gradient Descent, BERT, GPT, LangChain, Gen AI, DL Architectures (CNN, LSTM, Transformers)

**Packages:** Numpy, Pandas, Scipy, NLP Sklearn, Tensorflow, Keras, PySpark, Transformers, Flask, Seaborn, Plotly, LLM, LaMDA, LLaMa, AutoGPT or AgentGPT

**Tools/Micro-Controllers:** Python, SQL, MATLAB, Docker, Github, Jira, Confluence, Notion, Jetson nano, Arduino, ESP

**Data Science Techniques:** Text Analytics, Information Retrieval, Statistical Analysis, Mathematics, Data Manipulation

**Cloud & Serverless Architecture:** AWS Lambda, Amazon ECS (Fargate), Amazon EC2, Amazon SageMaker, Amazon Bedrock, Amazon S3, Sns, Sqs

---

## EDUCATION

**University of Management and Technology, BSc in Software Engineering**

- GPA: 3.7/4.0 (Topper)
- Coursework: Computer Architecture, Comparison of Learning Algorithms, Computational Theory

---

## PROJECTS

### Youbot <sub>Chat with any Youtube video instantly</sub>

Architected and deployed a production-ready RAG (Retrieval-Augmented Generation) platform that transforms long-form video content into actionable intelligence, enabling real-time semantic search and synthesis of YouTube transcriptions.

- Engineered a High-Performance Ingestion Pipeline: Built a custom data processing engine using LangChain and FastAPI that leverages parallel execution to ingest and index transcriptions from videos exceeding 10+ hours. Implemented intelligent chunking strategies with overlapping windows to maintain semantic context, reducing total processing latency by 70% compared to sequential baselines.
- Optimised Vector Storage & Retrieval: Designed and managed a vector database architecture using ChromaDB, implementing metadata filtering and custom similarity search parameters to ensure high-precision retrieval. Leveraged Gemini's long-context window capabilities alongside RAG to provide nuanced answers while minimising hallucinations.
- Implemented Asynchronous Stream Processing: Developed a non-blocking backend architecture utilising asyncio and FastAPI BackgroundTasks to handle high-concurrency workloads. Engineered a streaming LLM response layer using Server-Sent Events (SSE), providing a low-latency, "typewriter-style" UI experience for end-users.
- Architected Full-Stack Observability & Evaluation: Integrated LangSmith for granular tracing of the LLM chain, allowing for the monitoring of token consumption, cost-per-query, and retrieval relevancy. Built custom evaluation loops to benchmark response quality across different temperature settings and prompt templates.
- Advanced UI/UX Engineering: Translated complex Figma designs into a responsive React application featuring a robust state management system (Zustand/Redux) to track multi-stage ingestion progress (fetching, indexing, querying) in real-time, significantly improving user retention and perceived performance.
- Scalable Infrastructure & Data Integrity: Ensured system reliability by implementing Pydantic for strict schema validation across the API layer and developing error-handling middleware to gracefully manage YouTube API rate limits and transient network failures during heavy transcription loads.

### Documind <sub>Self-Service Document Intelligence & RAG Platform</sub>

- Architected and deployed a self-service document intelligence platform enabling end-users to curate personalised knowledge bases and perform instant semantic interrogation of private document repositories via a production-grade RAG ecosystem.
- Engineered a high-fidelity document processing pipeline using Docling for complex PDF and Word-to-text conversion, integrating an LLM-driven preprocessing layer that boosted chunk coherence by 30% through intelligent semantic boundaries.
- Optimised a high-dimensional vector search layer by leveraging Mistral-Embed for 768-dimensional embeddings and Supabase (pgvector) for indexing, achieving sub-second retrieval performance across large-scale unstructured datasets.
- Developed a high-concurrency orchestration layer using FastAPI to handle the full lifecycle of document ingestion and embedding, implementing a non-blocking architecture that reduced average streaming chat latency to 400ms.
- Architected a secure multi-tenant backend infrastructure utilising Supabase Row-Level Security (RLS) and Pydantic schema validation to ensure strict data isolation and maintain the integrity of user-specific document stores.
- Designed and implemented a performant React frontend featuring a real-time streaming chat interface and multi-stage upload progress tracking, resulting in a 25% increase in user engagement metrics during initial performance testing.
- Integrated automated evaluation loops to monitor retrieval precision and context adherence, enabling the continuous refinement of chunking strategies and prompt templates to eliminate hallucinations in generated responses.
- Built a scalable ingestion workflow for unstructured data that handles complex document layouts and table extraction, ensuring the downstream LLM receives clean and structured context for higher-quality synthesis and reasoning.

### AI VideoCaptionor <sub>High-Accuracy Automated Subtitling & Transcription Engine</sub>

- Architected and deployed an end-to-end automated subtitling engine that transforms raw video and audio assets into studio-quality SRT files, reducing manual captioning overhead by over 90% for content creators and enterprises.
- Integrated a high-performance transcription pipeline utilising OpenAI Whisper (Large) to support 100+ languages, achieving a Word Error Rate (WER) of less than 5% through optimised model inference and acoustic pre-processing.
- Engineered a precise synchronisation layer by leveraging MoviePy for high-fidelity audio extraction and Librosa for signal analysis, ensuring caption timestamp accuracy within a ±50ms threshold to maintain perfect visual-audio alignment.
- Developed an optimised audio pre-processing workflow that includes noise reduction and normalisation to enhance transcription reliability across diverse recording environments and low-quality source audio.
- Designed a responsive Streamlit orchestration dashboard that enables real-time caption previews and rapid SRT export, providing a seamless "Human-in-the-Loop" experience for final subtitle verification before deployment.
- Implemented a scalable execution model to handle large video file uploads and compute-intensive inference tasks, ensuring system stability and UI responsiveness during long-running background transcription jobs.
- Facilitated global accessibility compliance by automating the generation of standards-compliant closed captions, enabling content creators to meet ADA and international localisation requirements instantly.
- Streamlined multi-format export workflows by building custom conversion logic to handle various frame-rates and encoding standards, ensuring cross-platform compatibility for YouTube, social media, and enterprise LMS platforms.

### CLV-Vision <sub>Predictive Customer Lifecycle & Churn Intelligence Engine</sub>

- Architected and deployed an end-to-end predictive analytics platform that forecasts Customer Lifetime Value (CLV) and churn probability, enabling marketing teams to transition from reactive to proactive retention strategies.
- Engineered a high-dimensional feature store by aggregating petabytes of clickstream data, transaction history, and support logs, utilising automated ETL pipelines to generate over 500+ behavioural features including recency, frequency, and monetary (RFM) metrics.
- Developed a multi-stage modelling pipeline utilising a Bayesian Beta-Geometric/Negative Binomial Distribution (BG/NBD) model for purchase frequency and a Gamma-Gamma model for monetary value, achieving a 15% improvement in LTV forecasting accuracy over baseline linear models.
- Implemented a sophisticated churn prediction system using XGBoost with custom objective functions to handle class imbalance, delivering an AUC-ROC of 0.89 and identifying 80% of at-risk customers at least 30 days before churn.
- Integrated Model Interpretability (XAI) frameworks using SHAP and LIME to provide "Reason Codes" for every prediction, empowering the Customer Success team to understand the specific drivers behind individual churn risks.
- Designed and executed large-scale A/B experiments to validate model-driven interventions, resulting in a 12% reduction in churn rate and a 20% increase in campaign ROI through hyper-personalised discount allocation.
- Established a robust MLOps lifecycle using MLflow for experiment tracking and AWS SageMaker for model deployment, implementing automated retraining loops and drift detection to ensure model performance remained stable amid shifting consumer behaviour.
- Optimised inference infrastructure by implementing batch scoring for millions of users and real-time API endpoints for high-intent triggers, ensuring the marketing stack received actionable scores with sub-second latency.
- Delivered executive-level observability dashboards in Tableau that visualised cohort analysis, model uplift, and financial impact, bridging the gap between technical performance and business-critical KPIs.

---

## GITHUB ANALYTICS

<div align="center">

<!-- These cards are self-generated by .github/workflows/profile-cards.yml
     and served directly by GitHub, so they never break from third-party
     rate limits or outages. Run the workflow once to create them. -->
<img width="90%" src="https://raw.githubusercontent.com/abdullah-khan-aie/abdullah-khan-aie/main/profile-summary-card-output/default/0-profile-details.svg" alt="profile details"/>

<img width="32%" src="https://raw.githubusercontent.com/abdullah-khan-aie/abdullah-khan-aie/main/profile-summary-card-output/default/3-stats.svg" alt="stats"/>
<img width="32%" src="https://raw.githubusercontent.com/abdullah-khan-aie/abdullah-khan-aie/main/profile-summary-card-output/default/1-repos-per-language.svg" alt="repos per language"/>
<img width="32%" src="https://raw.githubusercontent.com/abdullah-khan-aie/abdullah-khan-aie/main/profile-summary-card-output/default/2-most-commit-language.svg" alt="most commit language"/>

<br/>

<img src="https://streak-stats.demolab.com?user=abdullah-khan-aie&hide_border=true&background=ffffff&ring=204ECF&fire=204ECF&currStreakLabel=204ECF&sideLabels=000000&dates=434343&currStreakNum=000000&sideNums=000000" alt="streak"/>

</div>

<!-- ░░░ CONTRIBUTION ACTIVITY GRAPH - white page, Toptal-blue line ░░░ -->
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=abdullah-khan-aie&bg_color=ffffff&color=000000&line=204ECF&point=000000&area=true&area_color=204ECF&hide_border=true" alt="activity graph"/>

---

## CONTRIBUTION SNAKE

<div align="center">

<!-- The snake is generated by the workflow in .github/workflows/snake.yml -->
<img src="https://raw.githubusercontent.com/abdullah-khan-aie/abdullah-khan-aie/output/github-contribution-grid-snake.svg" alt="snake animation"/>

</div>

---

<div align="center">

**Lahore, Pakistan | abdullah_khan.dev@proton.me**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:204ECF,55:1B3FA8,100:0A1B4D&height=110&section=footer" alt="footer"/>

</div>
