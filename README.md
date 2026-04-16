<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=220&section=header&text=Kankana%20Bera&fontSize=56&fontColor=e94560&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%E2%80%A2%20Computer%20Vision%20%E2%80%A2%20Android%20Developer&descAlignY=60&descSize=17&descColor=a8b2d8" width="100%" />

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kankana-bera)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kankanabera11@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kankanabera)

![Profile Views](https://komarev.com/ghpvc/?username=Kankanabera&color=e94560&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 👩‍💻 About Me

```python
class KankanaBera:
    def __init__(self):
        self.name      = "Kankana Bera"
        self.degree    = "B.Tech – Electronics & Computer Science @ KIIT"
        self.cgpa      = 8.85
        self.location  = "Bhubaneswar / Kolkata, India"
        self.focus     = ["Machine Learning", "Computer Vision", "Android Dev"]
        self.interned  = "Irisidea Technologies — AI/ML Computer Vision"
        self.fun_fact  = "I go from raw dataset → trained model → live mobile app 🚀"
```

- 🎓 **3rd-year B.Tech (ECS)** at KIIT, Bhubaneswar — CGPA **8.85**
- 💼 **AI/ML Intern** at Irisidea Technologies — built a production CV pipeline end-to-end
- 🏆 **Reliance Foundation Undergraduate Scholar** — selected among top students across India
- 🇮🇳 **Smart India Hackathon (SIH) Participant** — delivered a biodiversity assessment solution
- 🌱 Currently exploring **LSTMs, on-device TFLite inference, and RAG pipelines**

---

## 💼 Experience

### 🏢 AI/ML Intern — Computer Vision & Software Development
**Irisidea Technologies** &nbsp;|&nbsp; *May 2025 – October 2025*

> Built an end-to-end **liquid purity detection system** using CNNs and classical CV techniques — managing the full ML lifecycle from data collection to model serialization and live prediction.

- Multi-phase image analysis pipeline: pixel-wise difference → Otsu's thresholding → contour-based classification
- Implemented SSIM-based structural similarity, Laplacian variance blur detection, and morphological noise filtering
- Trained Logistic Regression classifier on BGR color features; evaluated with accuracy, precision, recall & confusion matrix
- Architected CNN roadmap: VGG16, ResNet, MobileNetV2, InceptionV3 for production scale

---

### 🏦 Software Engineering Virtual Experience
**J.P. Morgan Chase (via Forage)** &nbsp;|&nbsp; *Jan 2026 – Feb 2026*

> Simulated backend engineering in a fintech environment — Kafka integration, H2 in-memory database, and REST API development.

- Built and tested REST API endpoints and controllers in an enterprise-grade backend architecture
- Applied industry practices around system reliability, data integrity, and modular design

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌿 KrishiNoor — Plant Disease Detection
*Python · TensorFlow/Keras · FastAPI · Android (Kotlin)*

Dual-stage MobileNetV2 pipeline classifying **33 disease types across 9 crops** from leaf images. Farmers get instant, GPS-tagged diagnoses via a native Android app.

- Binary classifier (Healthy/Diseased) + 33-class multi-label identifier
- FastAPI REST backend with GPS-aware structured JSON responses
- Confidence-based decision engine: Alert Farmer / Monitor / Send to Expert

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kankanabera/smart-farming-uav)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td width="50%" valign="top">

### ♻️ EcoSort AI — Waste Classification App
*Java · Android Studio · TensorFlow Lite · XML*

On-device Android app classifying waste into **5 categories** (Plastic, Paper, Metal, Glass, Organic) — no internet needed, real-time inference with disposal guidance.

- Full TFLite inference pipeline: capture → 224×224 preprocessing → confidence output
- RecyclerView scan history with recyclability & compostability indicators
- Non-blocking UI via ExecutorService background thread inference

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kankanabera/Smart-Waste-Classifier)
![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 Stock Price Predictor — Multi-Company Forecasting
*Python · Flask · LSTM · Chart.js · HTML/CSS/JS*

Full-stack forecasting web app — pick a company, get a **7-day price forecast** visualized live via Chart.js. LSTM vs Linear Regression benchmarked head-to-head.

- Per-company LSTM models (.h5) with in-memory model cache for fast responses
- MSE benchmarking showed LSTM significantly outperforms Linear Regression
- Flask REST API backend + interactive JS frontend with dropdown selection

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kankanabera/Stock-Prediction)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)

</td>
<td width="50%" valign="top">

### 🏦 Thera Bank — Loan Analytics Dashboard
*Python · SQL · Plotly Dash · Pandas · Seaborn*

Analyzed **5,000 customer records** to find loan conversion opportunities — built an interactive Plotly Dash dashboard used to guide real marketing decisions.

- SQL segmentation by income, education, family size & product usage
- Heatmaps, box plots & demographic analysis to surface high-propensity profiles
- Multi-tab Bootstrap dashboard with dynamic KPI filters and cross-sell recommendations

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kankanabera)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 Liquid Purity Detection System
*Python · OpenCV · Scikit-learn · Pandas · Matplotlib*

CV pipeline detecting liquid purity from images — no specialized hardware. Progresses from SSIM structural analysis to full ML classification.

- SSIM + Laplacian variance + Otsu's thresholding + morphological filtering
- Logistic Regression on BGR color features with train/test evaluation
- Architected CNN upgrade path (VGG16, ResNet, MobileNetV2)

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kankanabera)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

</td>
<td width="50%" valign="top">

### 🤖 Chatbot with PDF Reader & Web Scraper
*Python · LLM · NLP*

Intelligent chatbot combining PDF document ingestion and live web scraping for conversational Q&A — answers questions grounded in your own documents plus real-time web context.

[![View Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Kankanabera/chatbot-with-pdf-reader-web-scrapper)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**AI / ML / Computer Vision**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Data & Visualization**

![Plotly](https://img.shields.io/badge/Plotly_Dash-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![MS Excel](https://img.shields.io/badge/MS_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Kankanabera&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kankanabera&layout=compact&langs_count=7&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Kankanabera&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🏆 Achievements & Certifications

| 🏅 | Achievement |
|---|---|
| 🎓 | **Reliance Foundation Undergraduate Scholarship** — Selected among top undergraduates across India on academic merit |
| 🇮🇳 | **Smart India Hackathon (SIH) Participant** — Delivered a biodiversity assessment solution under tight deadlines |
| ⚡ | **E-Labs Society, KIIT** — Active member in electronics & interdisciplinary innovation projects |

| 📜 Certification | Issuer | Year |
|---|---|---|
| AI-ML Virtual Internship (10 Weeks) | Google for Developers / AICTE & EduSkills | 2025 |
| DBMS – Fundamentals & Advanced Concepts | Scalar Academy | 2025 |
| Python Developer Certification | freeCodeCamp | 2026 |
| JavaScript Developer Certification | freeCodeCamp | 2026 |
| Legacy Responsive Web Design | freeCodeCamp | 2026 |

---

## 🌱 Currently Learning

- ☁️ Deploying ML models on AWS / GCP  
- 🧩 MLOps — model versioning & CI/CD pipelines  
- 📦 RAG pipelines & LLM application development

---

## 🤝 Let's Connect

I'm open to **AI/ML collaborations**, **open source contributions**, **research opportunities**, and **internships**. Feel free to reach out!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kankana-bera)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kankanabera11@gmail.com)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=120&section=footer" width="100%" />

*"First, solve the problem. Then, write the code."*

</div>
