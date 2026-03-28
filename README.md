# Gustavo Silva Nogueira

**AI Search & Artificial Intelligence Backend/Integrations Engineer**  
*Data Science · Edge AI · Local‑First Systems*

---

## 🛠️ Stack

| Área | Tecnologias |
|------|-------------|
| **IA Local** | LM Studio · Ollama · Hugging Face · Sentence‑Transformers · Nomic Embed |
| **Backend & API** | FastAPI · gRPC · Axum (Rust) · .NET 6 · GraphQL |
| **RAG & Busca** | LangChain · FAISS · Pinecone · ChromaDB · SQLite‑vec |
| **Data Science** | Pandas · NumPy · XGBoost · LightGBM · Prophet · scikit‑learn |
| **DevOps & Runtime** | Docker · ONNX · ONNX Runtime · TensorFlow Serving · GitHub Actions |
| **Linguagens** | Python · Rust · C# · C/C++ · Java · JavaScript |

---

## 📁 Projetos em Destaque

| Projeto | Stack | Descrição |
|---------|-------|-----------|
| [Edge Video RAG Agent](https://github.com/Gussnogue/edge-video-rag-agent) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Whisper](https://img.shields.io/badge/Whisper-OpenAI-412991?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-005A9C?style=flat-square&logo=meta&logoColor=white) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) | Pipeline RAG completo para vídeos: extração de áudio (yt-dlp/upload local), transcrição multilíngue (Whisper), sumarização (Hermes 3), embeddings (Nomic), indexação vetorial FAISS + SQLite, busca semântica. Interface Streamlit com ingestão individual/em lote, consulta por similaridade e dashboard analítico (métricas, nuvem de palavras, stopwords customizáveis). Totalmente offline, privado e extensível. |
| [Doc Audio Assistant](https://github.com/Gussnogue/doc-audio-assistant-rag-tts-langchain-kyutai) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-005A9C?style=flat-square&logo=meta&logoColor=white) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) ![Pocket TTS](https://img.shields.io/badge/Pocket%20TTS-FF6B6B?style=flat-square) | Assistente documental offline: upload de PDF/TXT → chunking → embeddings Nomic (LM Studio) → indexação FAISS → geração de respostas com Hermes 3 → síntese de fala com Pocket TTS (vozes éticas). Interface Streamlit para perguntas em português e áudio reproduzido. Totalmente local, privado e sem dependência de APIs pagas. |
| [Assistente Administrativo RAG](https://github.com/Gussnogue/assistente-administrativo-rag-langchain-ialocal-faiss) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![MarkItDown](https://img.shields.io/badge/MarkItDown-0078D4?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-005A9C?style=flat-square&logo=meta&logoColor=white) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) | Pipeline RAG local para PDFs: extração de texto com MarkItDown (Microsoft), chunking, embeddings com Nomic (sentence-transformers), indexação FAISS e geração de respostas com Hermes 3 (LM Studio). Interface Streamlit, 100% offline e privado. |
| [Azitech AI Search Assistant](https://github.com/Gussnogue/azitech_open_source_ai_search_assistant) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square) ![Groq](https://img.shields.io/badge/Groq-FF4B4B?style=flat-square) ![Fireworks](https://img.shields.io/badge/Fireworks-FF6B6B?style=flat-square) ![Together](https://img.shields.io/badge/Together-1C3C3C?style=flat-square) | Gateway multi‑provedor com roteador inteligente e fallback automático (Groq, Fireworks, Together, Replicate, Vercel). Módulos: analisador local (PDF, headings, metadados), assistente SEO, geração de código Python/Rust/C++, consulta etimológica. |
| [System Content Agents](https://github.com/Gussnogue/system-content-agents-ai-local) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FFD700?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square) | Sistema com agentes customizados (blog, social, SEO, URL, tradutor, ABNT), memória persistente via ChromaDB + embeddings Nomic, histórico em SQLite, guardrails de segurança e interface Streamlit. Totalmente offline. |
| [Tradutor Scilab com IA Local](https://github.com/Gussnogue/ai-local-lmstudio-scilab) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) ![Hermes 3](https://img.shields.io/badge/Hermes_3-3B-FFD700?style=flat-square) ![Scilab](https://img.shields.io/badge/Scilab-4B8BBE?style=flat-square) | Conversor de linguagem natural para código Scilab: descreva o problema em português (ex: "plote a função seno de 0 a 2π") → Hermes 3 gera o script Scilab → execução local automática. Interface Streamlit, tudo offline, privado e sem dependência de APIs externas. |
| [Manim AI Generator](https://github.com/Gussnogue/manim-ai-generator-animation-data-science) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square) ![Groq](https://img.shields.io/badge/Groq-FF4B4B?style=flat-square) | Geração de animações matemáticas com Manim a partir de linguagem natural usando Groq Llama 3.3. |
| [Hermes Math Studio](https://github.com/Gussnogue/hermes-math-studio-estatistica-e-visualizacao-ai-numpy-plotly-pytorch) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) | Ambiente integrado para análise de dados educacional e profissional. Módulos: NumPy (estatística descritiva, PCA, FFT, regressão linear), Plotly (visualizações 3D, mapas, séries temporais) e PyTorch (rede neural MNIST). IA local (Hermes 3) explica resultados com conceitos, fórmulas e fontes confiáveis. 100% offline. |
| [Rust AI Chat](https://github.com/Gussnogue/rust-ai-lmstudio-chat) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | Cliente CLI em Rust para interagir com modelos locais do LM Studio via API compatível com OpenAI. |
| [SEO Analyzer (Rust)](https://github.com/Gussnogue/Seo_Content_Analyzer_Rust) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | CLI em Rust puro para análise de texto: métricas de SEO, detecção de IA e análise de sentimento. |
| [BB84 QKD Simulator](https://github.com/Gussnogue/simulador-bb84-distribuicao-quantica-de-chaves) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square) | Simulação do protocolo BB84 de distribuição quântica de chaves. Detecção de espionagem via QBER e análise por IA local (Hermes 3). |
| [Simulador de Projétil com IA](https://github.com/Gussnogue/simulador-de-projetil-com-arrasto-linear-visualizacao-otimizacao-ai) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square) | Simulação física (arrasto linear) com método de Euler e otimização guiada por IA local (Hermes 3). Interface interativa. |
| [XGBoost Simulador de Demanda](https://github.com/Gussnogue/xgboost-prever-vendas-elasticidade-ai-local) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square) ![LM Studio](https://img.shields.io/badge/LM_Studio-0A0A0A?style=flat-square) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square) | Modelo preditivo XGBoost treinado com dataset BigMart Sales (8.523 produtos, 12 atributos). Simulação de elasticidade de preço com sliders interativos e geração de insights em linguagem natural via Hermes 3 (LM Studio). Interface Streamlit com gráficos Plotly e pipeline completo Local. |
| [XGBoost Real State](https://github.com/Gussnogue/xgboost-real-state-hermes-ai-local) | ![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square) | Previsão de preços de imóveis com XGBoost e interpretação de resultados por IA local. |
| [Time Series Analyzer](https://github.com/Gussnogue/time-series-analyzer-ai-hermes-kaggle) | ![Prophet](https://img.shields.io/badge/Prophet-FF6B6B?style=flat-square) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square) | Análise de séries temporais (clima de Delhi): decomposição, detecção de anomalias, previsão com Prophet e insights automáticos. |
| [MNIST Gradient Flow Analyzer](https://github.com/Gussnogue/mnist-gradient-flow-analyzer) | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square) | Visualização do fluxo de gradientes durante treinamento de rede neural no MNIST. |
| [Álgebra Linear 3D](https://github.com/Gussnogue/algebra-linear-matriz-3d) | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square) | Explorador interativo de álgebra linear com visualizações 3D: sistemas lineares, autovalores, decomposições QR/SVD. |
| [Dashboard de Orçamentos](https://github.com/Gussnogue/dashboard-inteligente-de-orcamentos-para-engenheiros) | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square) | Analisador de planilhas Excel com 6 painéis analíticos (distribuição, correlação, outliers) e IA opcional. |
| [CRUD C# .NET](https://github.com/Gussnogue/CRUD_w_Csharp_.NET6.0_PostgreSQL_WEB_Swagger) | ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | API RESTful em .NET 6 com Entity Framework, PostgreSQL e Swagger. Arquitetura em camadas, migrações versionadas. |
| [Gerenciador de Tarefas](https://github.com/Gussnogue/gerenciador-de-tarefas-com-sqlite-e-streamlit) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) | CRUD completo com autenticação bcrypt e banco SQLite. Sistema de permissões e atualização em tempo real. |
---

## 🎓 Formação

| Curso | Instituição | Ano |
|-------|-------------|-----|
| Técnico em Inteligência Artificial | IFNMG | 2027 (cursando) |
| Pós‑Graduação em Data Science | UNICV | 2026 (cursando) |
| Formação Rust Developer | DIO | 2025 |
| Formação C/C++ Developer | DIO | 2025 |
| Especialização em Quality Assurance | EBAC | 2023 |
| Especialização em Product Management | PM3 | 2022 |
| Bacharelado em Ciência e Tecnologia | UFVJM | 2021 |

---

## 🔗 Contato

- [LinkedIn](https://www.linkedin.com/in/gustavo-nogueira-6077401b9/)
- [Credly – Certificações](https://www.credly.com/users/gustavo-silva-nogueira/badges)
- [Lattes](http://lattes.cnpq.br/4683515420488994)
- [AZITech](https://azitech.com.br)
