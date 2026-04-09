# Hi, I'm Thiebaut 👋

I'm a data scientist based in **Gothenburg, Sweden**, transitioning from over eight years in academic astrophysics research. I decided to leave academia both because I wanted to settle permanently in Gothenburg, and because I felt the need to tackle new challenges where I can more directly help people in their daily lives. Among the topics I care most about: medicine, environment, and sport.

---

## Background

I hold a Licence and Master's degree in Physics from the **Ecole Normale Superieure Paris-Saclay**, a Master's degree in Astrophysics from the **Observatory of Paris**, a **PhD in Astrophysics from Universite Paris-Saclay**, and completed a postdoc in Astrophysics at **Chalmers University of Technology** in Gothenburg.

Over more than eight years of research, I developed solid expertise in Python programming and large-scale data analysis. I led data-driven projects applying a range of methods -- from statistical signal processing techniques (wavelet analysis, Monte Carlo methods) to machine learning -- that resulted in scientific publications and international presentations. This taught me to communicate with varied audiences, including non-specialists. Working in national and international teams reinforced for me the value of collaboration and the importance of confronting your ideas with others in order to improve.

Being an AI enthusiast, I am starting to see all the amazing things it can bring, but I also notice in my own work the risk of relying too heavily on it and losing deep understanding. In a future where many data scientists will have training focused primarily on machine learning, I believe my background in physics and astrophysics gives me a different and complementary profile. Most of my recent personal projects are developed with the help of LLMs, which I see as a powerful tool when used with critical thinking.

---

## What I work with

**Languages and tools:** Python (NumPy, SciPy, Pandas, Matplotlib, Dash/Plotly, Scikit-learn, TensorFlow, Optuna, MLflow), SQL, Fortran, LaTeX, GitHub, Railway

**Currently learning:** Azure Data Scientist certification (DP-100), React Native, Next.js

**Strengths:** team collaboration, student supervision, conference organisation, creative problem-solving, curiosity-driven, helpful mentorship

---

## Featured Projects

### [RADMC-3D Iterative Wrapper](https://github.com/Thiebauts/radmc3d-iterative-wrapper)

A Python framework developed during my postdoc at the Department of Space, Earth and Environment at Chalmers, for modelling the dust emission around evolved stars known as *water fountains* -- old stars with bipolar jets traced by water maser emission. The code wraps two astrophysics tools: [RADMC-3D](https://www.ita.uni-heidelberg.de/~dullemond/software/radmc-3d/) for Monte Carlo radiative transfer, and [Optool](https://github.com/cdominik/optool) for computing dust opacities from laboratory measurements of silicates by [Demyk et al. (2022)](https://doi.org/10.1051/0004-6361/202243815). The key challenge is that dust opacity depends on temperature, but temperature itself depends on opacity. The wrapper solves this by iterating: it classifies grid cells into temperature zones, assigns the corresponding opacity to each zone, reruns the simulation, and repeats until both the temperature field and the zone assignments converge. It also includes a parameter grid explorer for systematic exploration of the physical parameter space.

`Python` · `NumPy` · `Matplotlib` · `RADMC-3D` · `Optool`

---

### [Mean Blood Pressure](https://github.com/Thiebauts/MeanBloodPressure) & [BP OCR Bench](https://github.com/Thiebauts/bp-ocr-bench)

Built for someone who needed to read handwritten blood pressure logs several times a day, compute daily averages, and track trends over time. The app lets you photograph a handwritten log, sends the image to a vision LLM via [OpenRouter](https://openrouter.ai/), and returns structured readings that can be reviewed, edited, and exported as a PDF report.

To choose the right model, I built a separate benchmarking tool -- [BP OCR Bench](https://github.com/Thiebauts/bp-ocr-bench). With a friend, I created a dataset of handwritten notes at varying difficulty levels, then evaluated 18 vision models (from Google, OpenAI, Anthropic, Mistral, and others) on extraction accuracy, cost per request, and response time. The result: Gemini Flash 3.0 and Gemini 3.1 Flash Lite sit on the Pareto frontier, achieving 95–98% accuracy at ~$0.001/request -- two orders of magnitude cheaper than frontier models for comparable precision.

`TypeScript` · `Next.js` · `React` · `OpenRouter API` · `Vite` · `IndexedDB`

---

### [Triathlon Väst Dashboard](https://github.com/Thiebauts/triathlon-vast-dashboard)

I'm a member of [Triathlon Väst](https://www.triathlonvast.se/) in Gothenburg, a club that organises competitions in running, swimming, cycling, triathlon, duathlon, and swimrun throughout the year. That generates a lot of results data, so I built a dashboard where members can browse competition results, view athlete profiles, track accumulated points, and explore club rankings across seasons (2021–2025). The data comes from CSV exports of the competition management system, parsed and bundled at build time. The app is bilingual (Swedish/English) and open to contributions -- members can request features or submit pull requests directly.

`TypeScript` · `Next.js` · `React` · `Recharts` · `Tailwind CSS` · `Vercel`

---

### Kaggle Competitions

A collection of end-to-end machine learning projects from Kaggle Playground Series competitions and NeurIPS challenges. Each repo covers data exploration, feature engineering, model selection, hyperparameter tuning (Optuna), and ensemble strategies, with experiment tracking via MLflow or Azure ML. Topics range from churn prediction and flood forecasting to polymer property regression from molecular SMILES. All Kaggle project repositories are named with the `kaggle-` prefix.

`Python` · `Scikit-learn` · `LightGBM` · `XGBoost` · `CatBoost` · `Optuna` · `MLflow` · `PyTorch`

---

## Let's talk

🌐 [thiebautschirmer.com](https://www.thiebautschirmer.com) &nbsp;|&nbsp; 💼 [linkedin.com/in/thiebaut-schirmer](https://www.linkedin.com/in/thiebaut-schirmer/) &nbsp;|&nbsp; 📍 Gothenburg, Sweden
