# Hi, I'm Thiebaut 👋

I'm a data scientist based in **Gothenburg, Sweden**, transitioning from over eight years in academic astrophysics research. I decided to leave academia both because I wanted to settle permanently in Gothenburg, and because I felt the need to tackle new challenges where I can more directly help people in their daily lives. Among the topics I care most about: medicine, environment, and sport.

---

## Background

I hold a Licence and Master's degree in Physics from the **Ecole Normale Superieure Paris-Saclay**, a Master's degree in Astrophysics from the **Observatory of Paris**, a **PhD in Astrophysics from Universite Paris-Saclay**, and completed a postdoc in Astrophysics at **Chalmers University of Technology** in Gothenburg.

Over more than eight years of research, I developed solid expertise in Python programming and large-scale data analysis. I led data-driven projects applying a range of methods -- from statistical signal processing techniques (wavelet analysis, Monte Carlo methods) to machine learning -- that resulted in scientific publications and international presentations. This taught me to communicate with varied audiences, including non-specialists. Working in national and international teams reinforced for me the value of collaboration and the importance of confronting your ideas with others in order to improve.

Being an AI enthusiast, I am starting to see all the amazing things it can bring, but I also notice in my own work the risk of relying too heavily on it and losing deep understanding. In a future where many data scientists will have training focused primarily on machine learning, I believe my background in physics and astrophysics gives me a different and complementary profile. Most of my recent personal projects are developed with the help of LLMs, which I see as a powerful tool when used with critical thinking.

---

## What I work with

**Languages and tools:**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Plotly](https://img.shields.io/badge/Dash%2FPlotly-3F4F75?logo=plotly&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2980B9)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![Fortran](https://img.shields.io/badge/Fortran-734F96?logo=fortran&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)

**Currently learning:**

![Azure DP-100](https://img.shields.io/badge/Azure%20DP--100-0078D4?logo=microsoftazure&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=20232a)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)

**Strengths:** team collaboration, student supervision, conference organisation, creative problem-solving, curiosity-driven, helpful mentorship

---

## Featured Projects

### [RADMC-3D Iterative Wrapper](https://github.com/Thiebauts/radmc3d-iterative-wrapper)

A Python framework developed during my postdoc at the Department of Space, Earth and Environment at Chalmers, for modelling the dust emission around evolved stars known as *water fountains* -- old stars with bipolar jets traced by water maser emission. The code wraps two astrophysics tools: [RADMC-3D](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/) for Monte Carlo radiative transfer, and [Optool](https://github.com/cdominik/optool) for computing dust opacities from laboratory measurements of silicates by [Demyk et al. (2022)](https://doi.org/10.1051/0004-6361/202243815). The key challenge is that dust opacity depends on temperature, but temperature itself depends on opacity. The wrapper solves this by iterating: it classifies grid cells into temperature zones, assigns the corresponding opacity to each zone, reruns the simulation, and repeats until both the temperature field and the zone assignments converge. It also includes a parameter grid explorer for systematic exploration of the physical parameter space.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![RADMC-3D](https://img.shields.io/badge/RADMC--3D-444444)
![Optool](https://img.shields.io/badge/Optool-444444)

---

### [Mean Blood Pressure](https://github.com/Thiebauts/MeanBloodPressure) & [BP OCR Bench](https://github.com/Thiebauts/bp-ocr-bench)

Built for someone who needed to read handwritten blood pressure logs several times a day, compute daily averages, and track trends over time. The app lets you photograph a handwritten log, sends the image to a vision LLM via [OpenRouter](https://openrouter.ai/), and returns structured readings that can be reviewed, edited, and exported as a PDF report.

To choose the right model, I built a separate benchmarking tool -- [BP OCR Bench](https://github.com/Thiebauts/bp-ocr-bench). With a friend, I created a dataset of handwritten notes at varying difficulty levels, then evaluated 18 vision models (from Google, OpenAI, Anthropic, Mistral, and others) on extraction accuracy, cost per request, and response time. The result: Gemini Flash 3.0 and Gemini 3.1 Flash Lite sit on the Pareto frontier, achieving 95–98% accuracy at ~$0.001/request -- two orders of magnitude cheaper than frontier models for comparable precision.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=20232a)
![OpenRouter](https://img.shields.io/badge/OpenRouter%20API-6366F1)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![IndexedDB](https://img.shields.io/badge/IndexedDB-444444)

---

### [Triathlon Väst Dashboard](https://github.com/Thiebauts/triathlon-vast-dashboard)

I'm a member of [Triathlon Väst](https://www.triathlonvast.se/) in Gothenburg, a club that organises competitions in running, swimming, cycling, triathlon, duathlon, and swimrun throughout the year. That generates a lot of results data, so I built a dashboard where members can browse competition results, view athlete profiles, track accumulated points, and explore club rankings across seasons (2021–2025). The data comes from CSV exports of the competition management system, parsed and bundled at build time. The app is bilingual (Swedish/English) and open to contributions -- members can request features or submit pull requests directly.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=20232a)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

---

### [Triagegeist](https://github.com/Thiebauts/kaggle-triagegeist)

This was a particularly important project for me. I have a long-standing interest in medicine, and Triagegeist was the first time I could bring my data-science work into a clinical setting -- a combination I had been wanting to try for years. I built it as a one-person submission to the Laitinen-Fredriksson Foundation **ED Triage Acuity Hackathon** (April 2026), a $10k competition on emergency-department triage prediction.

The clinical problem: when patients arrive at an emergency department, a triage nurse assigns an *acuity level* (1 = resuscitation, 5 = non-urgent) on the Emergency Severity Index, and that decision determines how quickly they are seen. The two error modes are not symmetric. **Under-triage** -- assigning a lower acuity than warranted -- carries documented mortality risk (OR 1.24-2.18 for trauma deaths), whereas **over-triage** mostly wastes resources. Yet most ML triage models optimise for symmetric metrics like macro-F1, which treats both errors as equally costly. Triagegeist explicitly bakes that asymmetry into training, calibration, and threshold selection.

The pipeline fine-tunes [Bio_ClinicalBERT](https://huggingface.co/emilyalsentzer/Bio_ClinicalBERT) on chief-complaint free text, blends its embeddings with structured vitals through a gradient-boosted ensemble (LightGBM + XGBoost + CatBoost), then runs a Nelder-Mead optimisation over per-class thresholds to minimise an asymmetric under-triage cost. SHAP explanations and an intersectional bias audit (across age x sex x race subgroups) are built in -- both required for the EU AI Act Annex III §5(d) compliance mapping included in the submission. The model was validated on **80k synthetic Kaggle encounters and 418k real MIMIC-IV-ED visits**, where it matched live nurse-to-expert inter-rater reliability (κ = 0.701 vs published 0.694) and reduced overall under-triage from 15.2% to 6.1% while shrinking the worst-subgroup disparity ratio from 2.47 to 1.43.

The repository ships with a runnable Kaggle notebook, a ~125-page LaTeX report covering full methodology and ablations, the hackathon writeup, and aggregate MIMIC-IV-ED supplementary results (figures + JSON/CSV summaries only -- no patient-level data, in line with PhysioNet's data-use agreement).

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![Bio_ClinicalBERT](https://img.shields.io/badge/Bio__ClinicalBERT-444444)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00)
![SHAP](https://img.shields.io/badge/SHAP-2EB6BC)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

---

### Kaggle Competitions

A collection of end-to-end machine learning projects from Kaggle Playground Series competitions and NeurIPS challenges. Each repo covers data exploration, feature engineering, model selection, hyperparameter tuning (Optuna), and ensemble strategies, with experiment tracking via MLflow or Azure ML. Topics range from churn prediction and flood forecasting to polymer property regression from molecular SMILES. All Kaggle project repositories are named with the `kaggle-` prefix.

- [kaggle-polymer-properties](https://github.com/Thiebauts/kaggle-polymer-properties) -- 5 polymer properties from SMILES | Random Forest + ChemBERTa (NeurIPS 2025)
- [kaggle-irrigation-prediction](https://github.com/Thiebauts/kaggle-irrigation-prediction) -- Irrigation classification | BA = 0.971 | class weighting + ensemble
- [kaggle-customer-churn](https://github.com/Thiebauts/kaggle-customer-churn) -- Churn classification | AUC = 0.914 | greedy ensemble from 75 experiments
- [kaggle-flood-prediction](https://github.com/Thiebauts/kaggle-flood-prediction) -- Flood prediction regression | R² = 0.869 | LightGBM + feature engineering

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00)
![Optuna](https://img.shields.io/badge/Optuna-2980B9)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

---

## Let's talk

🌐 [thiebautschirmer.com](https://www.thiebautschirmer.com) &nbsp;|&nbsp; 💼 [linkedin.com/in/thiebaut-schirmer](https://www.linkedin.com/in/thiebaut-schirmer/) &nbsp;|&nbsp; 📍 Gothenburg, Sweden
