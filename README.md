# Aaditya Amlan Panda

**`@Aadityaamlan-Panda`** · Chemical engineer who codes. I build process simulations, ML pipelines, NLP tools, and numerical solvers — bridging thermodynamics and software. Final year B.Tech, IIT Kanpur.

![Process Simulation](https://img.shields.io/badge/Process%20Simulation-1D9E75?style=flat-square&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-534AB7?style=flat-square&logoColor=white)
![Numerical Methods](https://img.shields.io/badge/Numerical%20Methods-BA7517?style=flat-square&logoColor=white)
![NLP / AI](https://img.shields.io/badge/NLP%20%2F%20AI-D85A30?style=flat-square&logoColor=white)
![Control Systems](https://img.shields.io/badge/Control%20Systems-185FA5?style=flat-square&logoColor=white)
![Economic Analysis](https://img.shields.io/badge/Economic%20Analysis-1D9E75?style=flat-square&logoColor=white)

---

## 🛠 Technical Skills

### Languages & Tools
![Python](https://img.shields.io/badge/Python-534AB7?style=flat-square&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-534AB7?style=flat-square&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-534AB7?style=flat-square&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-555?style=flat-square&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-555?style=flat-square&logoColor=white)
![Git](https://img.shields.io/badge/Git-555?style=flat-square&logoColor=white)
![HTML/CSS/JS](https://img.shields.io/badge/HTML%2FCSS%2FJS-555?style=flat-square&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-555?style=flat-square&logoColor=white)

### Process & Simulation
![Aspen Plus](https://img.shields.io/badge/Aspen%20Plus-1D9E75?style=flat-square&logoColor=white)
![Aspen EDR](https://img.shields.io/badge/Aspen%20EDR-1D9E75?style=flat-square&logoColor=white)
![Pinch Analysis](https://img.shields.io/badge/Pinch%20Analysis-555?style=flat-square&logoColor=white)
![TEMA HX Design](https://img.shields.io/badge/TEMA%20HX%20Design-555?style=flat-square&logoColor=white)
![PFR/CSTR](https://img.shields.io/badge/PFR%20%2F%20CSTR-555?style=flat-square&logoColor=white)
![Distillation](https://img.shields.io/badge/Distillation-555?style=flat-square&logoColor=white)
![Cogeneration](https://img.shields.io/badge/Cogeneration-555?style=flat-square&logoColor=white)

### Python Libraries
`NumPy` · `Pandas` · `Matplotlib` · `Scikit-learn` · `NLTK` · `Streamlit` · `OpenCV` · `MediaPipe` · `NetworkX` · `Pyvis` · `Requests` · `PyDub`

### MATLAB & Numerical Methods
`ode45 / ode78 / ode15s` · `bvp4c` · `pdepe` · `fmincon` · `lsqnonlin` · `FDM / MOL` · `RK4` · `Ziegler-Nichols` · `Tyreus-Luyben` · `IMC tuning`

---

## 📁 Projects

### 🔬 Methyl Benzoate Process Design — Capstone
**CHE453 · Prof. Raghavendra Ragipani · Aug 2025 – Ongoing**

`Aspen Plus` `TEMA` `Pinch Analysis` `Cogeneration`

Full industrial design of a continuous methyl benzoate plant via esterification of benzoic acid with methanol (HCl-catalysed). Thermodynamic model selected as UNIQUAC by fitting NIST VLE data; azeotrope analysis confirmed separation feasibility. Two four-column distillation sequences compared; Method 2 selected for lower peak reboiler duty. Shell-and-tube heat exchanger designed per TEMA, validated against Aspen EDR. Pinch analysis performed for heat exchanger network (ΔT_min = 10 °C). Rankine cogeneration cycle integrated for on-site power generation.

Turbulent PFR hydrodynamics analysed; recycle strategy implemented for >99% overall conversion. Sensitivity analysis on key variables for profit maximisation. Complete material and energy balances validated column-wise.

| Metric | Value |
|---|---|
| Product recovery | 98%+ |
| Energy consumption reduction | 50% |
| Payback period | ~3 years |
| Team size | 8 members |

---

### ⚙️ Ethyl Benzene Process Optimisation
**CHE352 · Prof. Nitin Kaistha · Mar – Apr 2025**

`MATLAB` `fmincon` `Ziegler-Nichols` `Tyreus-Luyben`

End-to-end optimisation framework: static sensitivity analysis followed by MATLAB `fmincon` achieving a **47.6% TAC reduction** from baseline. Three-column distillation network with heat integration for a 3-year payback at 99.9 kmol/h capacity. Dual-tuning control systems designed using Ziegler-Nichols and Tyreus-Luyben for superior dynamic response. Industrial-scale material and energy balances fully validated.

---

### 📈 ML Financial Risk Analytics Platform
**Self project · Aug – Sep 2025**

`Python` `Random Forest` `FinBERT` `Streamlit`

Production-ready pipeline combining Random Forest with FinBERT sentiment analysis — **60%+ directional accuracy** on real market data. Comprehensive risk management: VaR, Sharpe ratio, and regulatory compliance monitoring in a Streamlit dashboard. Feature engineering includes SMA, volatility indicators, and live news sentiment for market dynamics.

---

### 🔐 ML-PUF Response Modeling with SVM
**CS771 · Prof. Purushottam Kar · Mar – Apr 2025**

`Python` `Scikit-learn` `LinearSVC` `Feature Engineering`

End-to-end ML pipeline for Multi Level PUF (two Arbiter PUFs with XOR) response prediction from 8-bit challenges. Designed an 85-D feature set from challenge bits, integrated a polynomial kernel (deg-2) for linear separability. Trained and tuned `LinearSVC` reaching **100% accuracy**. Framed delay-recovery as a linear system; produced valid non-negative delay vectors for 64-bit Arbiter PUF models.

---

### 💰 Profitability Analysis of a Manufacturing Plant
**CHE352 · Prof. Nitin Kaistha · Mar – Apr 2025**

`Python` `DCF` `SOYD` `DDB`

SOYD and DDB depreciation methods for tax-optimised asset valuation. Full discounted cash flow forecasting: NPV, IRR, and payback period. Visual dashboards for plant cash flows and NPV sensitivity. Flexible interface for customisable depreciation selection and scenario analysis.

---

### 🤖 Local AI Chat Interface with Source Integration
**Self project · Jul – Aug 2025**

`Python` `Ollama` `NLTK` `RAG` `Tkinter`

Tkinter chatbot with Chat, Search, and AI+RAG modes. Ollama local LLM inference with NLTK-based intent router across Wikipedia, arXiv, Wolfram, news, weather, YouTube, and image fetchers. Full retrieval pipeline: intent detection → source selection → evidence retrieval → Markdown-to-HTML rendering. Threaded I/O with pygame audio playback and graceful fallbacks.

---

### 🧬 Bacterial Chemotaxis using Keller-Segel Model
**CHE497 Undergraduate Project · Prof. Akash Choudhary · Oct – Nov 2024**

`MATLAB` `PDE` `RK4` `Method of Lines`

Coupled PDE systems for bacterial concentration dynamics against ammonia gradient stimuli. Keller-Segel model implemented in MATLAB via RK4. Analytical solutions derived through separation of variables; finite difference schemes used for validation. Method of Lines with ode45/ode78 for enhanced numerical stability and computational efficiency.

---

### 🏗 Three-Tank Control System Optimisation
**CHE381 · Prof. Ishan Bajaj · Oct – Nov 2024**

`MATLAB` `PID` `Ziegler-Nichols` `Skogestad IMC`

PID optimisation framework minimising Integral Absolute Error — achieved **2.4557 IAE**. Comprehensive comparison of Ziegler-Nichols, Skogestad IMC, and Robust Response Time tuning methods on a three-tank cascade. Classical PI improved by **84%** via simulation fine-tuning. Optimised PID delivers **4× better performance** versus classical PI for third-order systems.

---

### 🗺 Interactive NLP Concept Mapping Tool
**Self project · Dec 2024 – Jan 2025**

`Python` `Streamlit` `NLTK` `NetworkX` `Pyvis`

Streamlit app for dynamic concept graph visualisation from text paragraphs. NLTK tokenisation, TF-IDF vectorisation, and cosine similarity to construct directed semantic graphs. NetworkX PageRank and Dijkstra's shortest path for node scoring and sequencing. Pyvis interactive networks with physics parameter controls and combined multi-paragraph concept mapping.

---

### ⚗️ Experimental Determination of Reaction Order
**CHE331 · Prof. Raj Ganesh S. Pala · Oct – Nov 2024**

`Python` `Kinetics` `Spectrophotometry` `Curve Fitting`

Determined reaction order of methylene blue photo-degradation promoted by H₂O₂ using kinetic analysis. Multi-order kinetic modelling with R² = 0.9329 for zeroth order. High-precision spectrophotometry with minute-by-minute kinetic monitoring. Demonstrated concentration-dependent order shift from first to zeroth as H₂O₂ concentration decreases.

---

### 🎬 Multilingual Video Dubbing Tool
**Self project · Jun – Jul 2024**

`Python` `Streamlit` `PyDub` `FFmpeg` `Google APIs`

Streamlit app integrating speech recognition, Google Translate, and text-to-speech. Automated audio processing pipeline using PyDub and FFmpeg: silence detection, audio segmentation, and time-stretching algorithms to preserve video timing. Google Speech-to-Text integration with efficient error handling. Automated SRT subtitle generation and video-audio sync with cross-platform FFmpeg fallbacks.

---

### 🏭 McCabe-Thiele Distillation Analysis
**CHE213 · Prof. Soumik Das · Mar – Apr 2024**

`Python` `VLE` `Curve Fitting` `Visualisation`

Advanced distillation column design using the McCabe-Thiele graphical method for multi-section columns with side stream withdrawal. Equilibrium curve modelled by fitting experimental VLE data with advanced curve fitting. Operating line construction to determine optimal reflux ratios. Automated theoretical tray calculation with visualisation for column design and separation performance insights.

---

### 🏗 Chemical Industry Feasibility Analysis
**CHE261 · Prof. Raghavendra Ragipani · Mar – Apr 2024**

`Economic Analysis` `Reactor Design` `Market Analysis`

Comprehensive design, synthesis, and strategic market analysis of key industrial chemicals. Economic feasibility and profit margin analysis for product positioning. Reactor sizing (578 L), production capacity up to 1000 kg/day, capital investment planning (~$50k). Import/export data analysis informing competitive strategies and regulatory compliance.

---

## 💼 Work Experience

### Student Mentor Intern — Rankguru Technology Solutions Pvt. Ltd.
**Oct 2024 – Jan 2025**

- Designed and solved 12+ end-to-end problem statements and 18 functional prototypes to guide student hackathons and 15+ school innovation initiatives
- Built 8 lightweight Python models paired with HTML/CSS/JS interfaces, reducing frontend complexity by 60%
- Integrated Cohere Chat API and 10 Microsoft Azure APIs; designed clean API wrappers, prompt flows, and error-handling pipelines
- Developed 5 OpenCV + MediaPipe automation pipelines for perception and interaction tasks; implemented multimedia apps for video and audio processing

---

## 📬 Contact

[![GitHub](https://img.shields.io/badge/GitHub-Aadityaamlan--Panda-181717?style=flat-square&logo=github)](https://github.com/Aadityaamlan-Panda)
[![Email](https://img.shields.io/badge/Email-aadityaap22@iitk.ac.in-D85A30?style=flat-square&logo=gmail&logoColor=white)](mailto:aadityaap22@iitk.ac.in)
![Phone](https://img.shields.io/badge/Phone-%2B91--8093756736-1D9E75?style=flat-square)
![Institute](https://img.shields.io/badge/IIT%20Kanpur-2022--2026-534AB7?style=flat-square)
