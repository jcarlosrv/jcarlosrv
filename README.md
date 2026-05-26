# Juan Carlos Ruelas

**Data Scientist & ML Engineer** — full ML lifecycle delivery for enterprise and public-sector clients at [Quant16](https://quant16.com) (part of EKI
Digital). Remote from Chihuahua, Mexico.

PhD in theoretical physics (quantum gravity). Peer-reviewed publications in *Physical Review D* and *Annals of Physics*. The combination trained me for
the two things modern data work actually demands: mathematical rigor under uncertainty, and patience to extract clean signal from noisy data.

---

## What I work on

- **Modeling** — scikit-learn, XGBoost, LightGBM, TensorFlow. Forecasting, classification, spend analytics.
- **LLM applications** — Claude API, LangChain, RAG pipelines, vector search (ChromaDB), evaluation harnesses.
- **Data engineering** — Python, SQL (PostgreSQL), MongoDB, REST APIs, ETL/ELT on Azure and GCP.
- **Analytics delivery** — Power BI (DAX, Microsoft Fabric, Power Query/M), Streamlit, Plotly.

## Teaching

Part-Time Professor at **Tecnológico de Monterrey** — Calculus, Linear Algebra, Statistics, and Data Science.

## Featured projects

### [Paper-RAG](https://github.com/jcarlosrv/paper-rag)
RAG over arXiv LLM-evaluation papers — Claude + ChromaDB + LangChain + Streamlit.
Ships with a reproducible eval harness measuring in-corpus accuracy, adversarial refusal rate, and false-grounding rate. See `EVAL.md` for the methodology
 and the baseline-vs-final iteration story.

**Live demo:** [paper-rag2.streamlit.app](https://paper-rag2.streamlit.app/)

### [Photometric Redshift Regression](https://github.com/jcarlosrv/photo-z-regression)
XGBoost model that predicts galaxy redshifts from SDSS photometric magnitudes.
Replicates the core photo-z ML pipeline used in modern sky surveys.

**Live demo:** [photo-z-regression.streamlit.app](https://photo-z-regression.streamlit.app/)

### [Energy Demand Forecasting](https://github.com/jcarlosrv/energy-demand-forecasting)
Hourly electricity load forecasting for Germany. LightGBM with lag, calendar, and weather features beats Prophet and a seasonal-naive baseline by ~6× on
MAE (447 MW vs 2,558–2,950 MW, MAPE 0.82%) on a held-out 2019 test set. End-to-end pipeline: OPSD + Open-Meteo ingestion → feature engineering → modeling
→ residual diagnostics → 7-day recursive forward forecast.

## Selected publications

- [Effective loop quantum geometry of Schwarzschild interior](https://doi.org/10.1103/PhysRevD.95.064041) — *Physical Review D*, 2017
- [Effective dynamics of the Schwarzschild black hole interior with inverse triad corrections](https://doi.org/10.1016/j.aop.2021.168401) — *Annals of
Physics*, 2021
- [Path integral polymer propagator of relativistic and nonrelativistic particles](https://doi.org/10.1103/PhysRevD.95.065026) — *Physical Review D*, 2017

## Contact

- LinkedIn — [linkedin.com/in/juan-ruelas](https://www.linkedin.com/in/juan-ruelas/)
- Email — j.carlos.ruelas.v@gmail.com
