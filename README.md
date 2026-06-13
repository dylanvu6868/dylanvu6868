<!-- ===================== HEADER BANNER ===================== -->
<a href="https://dylanvu6868.github.io/">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:20232a,50:5B21E0,100:61dafb&height=210&section=header&text=Vu%20Hai%20Duong&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20Computer%20Vision%20%C2%B7%20RAG%20%C2%B7%20On-device%20ML%20%C2%B7%20Hanoi&descAlignY=56&descSize=17" alt="header"/>
</a>

<!-- ===================== TYPING INTRO ===================== -->
<div align="center">
  <a href="https://dylanvu6868.github.io/">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=23&duration=3000&pause=800&color=61DAFB&center=true&vCenter=true&width=620&lines=I+turn+research+into+systems+that+ship.;Computer+Vision+%2B+Retrieval-Augmented+LLMs;Runs+in+the+real+world+%E2%80%94+even+on+a+%24200+phone.;Final-year+AI+%40+FPT+University." alt="Typing SVG" />
  </a>
</div>

<!-- ===================== BADGES ===================== -->
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=dylanvu6868&style=for-the-badge&color=5b21e0&label=PROFILE+VIEWS" alt="profile views"/>
  <img src="https://img.shields.io/badge/Based%20in-Hanoi,%20Vietnam-da251d?style=for-the-badge" alt="location"/>
  <img src="https://img.shields.io/badge/Open%20to-AI%20%2F%20ML%20roles-2ea44f?style=for-the-badge" alt="open to work"/>
</div>

<br/>

<!-- ===================== ABOUT ME ===================== -->
<table align="center">
  <tr>
    <td valign="top" width="58%">

#### 👋 About Me

Final-year **Artificial Intelligence** student at **FPT University**,
working where models meet messy reality.

I work across the full stack of applied AI — from cleaning raw **EEG
signals** in a research lab, to labelling and training **object detectors**
on a food-processing factory floor, to wiring up **hybrid retrieval** so a
language model gives answers it can actually cite.

I care most about the unglamorous parts: the **preprocessing** that makes a
model robust, the **quantisation** that gets it onto a cheap device, and the
**evaluation** that proves it works.

```yaml
name:      Vu Hai Duong (Dylan Vu)
location:  Xuan Mai, Hanoi 🇻🇳
focus:     Computer Vision · RAG · On-device ML
stack:     Python · PyTorch · FastAPI
languages: [Vietnamese, English (B2), Japanese]
motto:     "Get models out of the notebook."
```

  </td>
  <td valign="top" width="42%">

#### 📌 At a Glance

| Metric | Value |
|---|---|
| 🎯 Test acc · AgriRAG | **99.0%** |
| ⚡ On-device latency | **74 ms** |
| 🎓 CGPA | **3.42 / 4.0** |
| 🏆 Excellent Student | **Fall 2025** |

#### 🌐 Connect

<a href="https://dylanvu6868.github.io/"><img src="https://img.shields.io/badge/Portfolio-5B21E0?style=for-the-badge&logo=firefox&logoColor=white"/></a>
<a href="mailto:dylanvu6868@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/duong-hai-vu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/dylanvu6868"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

  </td>
  </tr>
</table>

<!-- ===================== SNAKE DIVIDER ===================== -->
<img width="100%" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="snake animation"/>

<!-- ===================== WHAT I BUILD ===================== -->
<h2 align="center">🧠 Three Things I Build Well</h2>

<table align="center">
  <tr>
    <td valign="top" width="33%" align="center">
      <h3>👁️ Computer Vision</h3>
      Detection & recognition pipelines that survive real-world noise — YOLOv8, Vietnamese-receipt OCR, and classification under class imbalance.
      <br/><br/>
      <code>YOLOv8</code> <code>OpenCV</code> <code>PaddleOCR</code> <code>VietOCR</code> <code>EfficientNet</code>
    </td>
    <td valign="top" width="33%" align="center">
      <h3>🔎 LLM + RAG</h3>
      Grounded generation that shows its sources — hybrid dense + keyword retrieval, reciprocal-rank fusion, cross-encoder re-ranking, structure-aware chunking.
      <br/><br/>
      <code>FAISS</code> <code>BM25</code> <code>RRF</code> <code>LangChain</code> <code>LLaMA 3.3</code> <code>RAGAS</code>
    </td>
    <td valign="top" width="33%" align="center">
      <h3>⚙️ ML Engineering</h3>
      Getting models out of the notebook — FP16/TFLite quantisation, latency & memory budgeting for mid-range hardware, FastAPI + SSE streaming.
      <br/><br/>
      <code>PyTorch</code> <code>TensorFlow</code> <code>TFLite</code> <code>Docker</code> <code>FastAPI</code>
    </td>
  </tr>
</table>

<br/>

<!-- ===================== FEATURED PROJECT ===================== -->
<h2 align="center">🚀 Featured Project</h2>

<div align="center">

### 🌾 AgriRAG — Rice Leaf Disease Recognition with RAG

</div>

> Diagnoses **10 rice-leaf diseases** from a photo, then explains the treatment **with citations**.
> EfficientNetB0 + two-stage transfer learning hits **99.01% test accuracy** across 15,023 images
> (Focal Loss + inverse-frequency weighting for a 1.8:1 imbalance). The grounded-answer layer is a
> hybrid RAG pipeline (FAISS + BM25 + RRF + cross-encoder re-rank) over a ~340-page agricultural
> corpus, served by FastAPI + SSE on LLaMA-3.3-70B — **FP16-quantised TFLite, runs offline on a mid-range Android phone.**

<div align="center">

| Macro F1 | Latency (Snapdragon 680) | RAGAS Faithfulness | On-device RAM |
|:---:|:---:|:---:|:---:|
| **0.989** | **74 ms** | **0.91** | **~195 MB** |

<a href="https://github.com/dylanvu6868/AgriRAG"><img src="https://img.shields.io/badge/View%20Code-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<!-- ===================== OTHER PROJECTS ===================== -->
<h2 align="center">🛠️ More Things I've Shipped</h2>

<table align="center">
  <tr>
    <td valign="top" width="50%">
      <h4>🧬 <a href="https://github.com/dylanvu6868/HDD-EEGMagicImage">EEG → Image (CLIP-StyleGAN)</a></h4>
      Turns EEG signals into images — spectrogram/recurrence-plot encoding, then a CLIP-guided StyleGAN scored with FID/IS.<br/>
      <code>PyTorch</code> <code>CLIP</code> <code>StyleGAN</code> <code>EEG</code>
    </td>
    <td valign="top" width="50%">
      <h4>📰 <a href="https://github.com/dylanvu6868/telegram-news-ai-bot">Realtime News AI Bot</a></h4>
      Telegram bot that gathers, de-dupes, ranks & summarises the day's news — pluggable search, Gemini summaries, Docker + systemd.<br/>
      <code>Gemini</code> <code>Tavily/Brave</code> <code>Docker</code>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>🎭 Deepfake Detection</h4>
      Classifies video as real or manipulated, with dedicated face extraction to lift reliability on facial-forgery datasets.<br/>
      <code>TensorFlow</code> <code>OpenCV</code> <code>Deep Learning</code>
    </td>
    <td valign="top" width="50%">
      <h4>🎬 Film Recommendation System</h4>
      Hybrid content-based + collaborative recommender with EDA, text mining & sentiment analysis.<br/>
      <code>Scikit-learn</code> <code>NLTK</code> <code>VADER</code> <code>TF-IDF</code>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>🍳 <a href="https://github.com/dylanvu6868/Cooking_Chatbot_Basics">Cooking Chatbot</a></h4>
      NLP recipe chatbot — a PyTorch network classifies the query, then retrieves matching recipes.<br/>
      <code>PyTorch</code> <code>NLP</code> <code>NLTK</code>
    </td>
    <td valign="top" width="50%">
      <h4>📄 <a href="https://github.com/dylanvu6868/CHATBOT_IN4PDF">Chat-with-PDF (RAG)</a></h4>
      Answers questions over a PDF — embed, retrieve relevant chunks, ground every answer in the source.<br/>
      <code>LangChain</code> <code>RAG</code> <code>Embeddings</code>
    </td>
  </tr>
</table>

<br/>

<!-- ===================== JOURNEY ===================== -->
<h2 align="center">🧭 The Path So Far</h2>

<div align="center">

```mermaid
timeline
    title From Signals to Shipped Systems
    2022 : Started BSc in AI — FPT University
    Mar 2024 : Research Trainee — FPT AI Research Lab (EEG, model robustness)
    Apr 2025 : AI Intern — C.P. Vietnam (YOLOv8 pig detection, VN-receipt OCR)
    2025 : Shipped AgriRAG (offline on a mid-range phone)
    2026 : Graduating — Open to AI / ML roles
```

</div>

<!-- ===================== TECH STACK ===================== -->
<h2 align="center">🧰 Tools of the Trade</h2>
<br/>

<div align="center">

**Languages**
<br/>
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>

**Frameworks & Libraries**
<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>

**Tools & Cloud**
<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white"/>
<img src="https://img.shields.io/badge/IBM%20Cloud-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white"/>

</div>

<br/>

<!-- ===================== GITHUB STATS ===================== -->
<h2 align="center">📊 GitHub Stats</h2>
<br/>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=dylanvu6868&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true&title_color=61dafb&text_color=ffffff&icon_color=5b21e0&bg_color=20232a" alt="stats"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=dylanvu6868&theme=radical&hide_border=true&background=20232A&ring=61dafb&fire=5b21e0&currStreakLabel=61dafb" alt="streak"/>
</div>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dylanvu6868&layout=compact&langs_count=8&theme=radical&hide_border=true&title_color=61dafb&text_color=ffffff&icon_color=5b21e0&bg_color=20232a" alt="top langs"/>
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=dylanvu6868&theme=react-dark&bg_color=20232a&color=61dafb&line=5b21e0&point=ffffff&hide_border=true" alt="activity graph"/>
</div>

<!-- ===================== HONORS ===================== -->
<h2 align="center">🏅 On the Record</h2>
<div align="center">

🥇 **Excellent Student of the Trimester** — Highest distinction · Fall 2025
🎖️ **Honorable Student of the Trimester ×4** — Fall 2024 · Spring 2025 · Summer 2025 · Spring 2026
📜 ML & Deep Learning Specializations · NLP · Applied Data Science with R · IBM Full-Stack Developer · English B2

</div>

<br/>

<!-- ===================== FOOTER ===================== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:61dafb,50:5B21E0,100:20232a&height=130&section=footer&text=Let's%20build%20something.&fontSize=26&fontColor=ffffff&animation=fadeIn&fontAlignY=68&desc=dylanvu6868@gmail.com&descAlignY=88" alt="footer"/>
