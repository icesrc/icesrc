# Hey, I'm Anirudh 

I'm pivoting into data science and MLOps — not dabbling, actually building. My background has a research side to it (biological data, network analysis) and I've been working to close the gap between a model that works in a notebook and one that works in production.

Most of what I'm building right now sits at that intersection — operational forecasting, deployment pipelines, and understanding what the data is actually saying before trusting any model to say it.

---

## Projects

**[analytics-mlops](https://github.com/icesrc/analytics-mlops)**
I wanted to answer one practical question: what does a full MLOps workflow actually look like, end to end? The result is a pipeline that goes from a raw daily metrics export through EDA, three ML models compared with time-series-correct cross-validation, a production retraining script, an HTML report, and two AI agent integrations. One injects insights into the report automatically. The other simulates how different teams would react to a proposed system change. Works on any daily KPI dataset — swap the CSV and run.

**[mlops-initial-learning](https://github.com/icesrc/mlops-initial-learning)**
Where I started learning the deployment side of ML. Takes a scikit-learn model through the full production path: FastAPI inference endpoint, Docker containerisation with a multi-stage build, Kubernetes deployment via Minikube with replica scaling and auto-generated Swagger docs. The model is Iris — the point wasn't the model, it was learning the infrastructure around it.

**[expression-pattern-analysis](https://github.com/icesrc/expression-pattern-analysis)**
Gene co-expression network analysis in R. Used WGCNA on a clinical dataset to look for relationships between nutritional biomarkers (vitamin D, calcium) and insulin sensitivity. Age and BMI clustered into statistically significant modules (p < 0.05) — the nutritional biomarker hypothesis didn't survive correction. That finding is in the repo. A clean null that rules something out is still useful.

**[canvas-copy-macos-port](https://github.com/icesrc/canvas-copy-macos-port)**
Older hobby project — a macOS automation tool for a pixel art canvas game. Not data science, just something I built for fun that ended up being a decent exercise in keyboard event handling and clipboard automation with pynput.

---

## Stack

Python · R · scikit-learn · PyTorch · FastAPI · Docker · Kubernetes · WGCNA · Jupyter · Ollama

---

## Get in touch

[Email](mailto:[anirudhsingh1915@gmail.com])
