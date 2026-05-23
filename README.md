# IELE756 – Final Project: One Anomaly, Defended

**Team 16:** Sofía Fariña and Martina Retamales  
**Course:** IELE756 – Preparación y Análisis de Datos  
**Professor:** Leo Ferres  
**Universidad del Desarrollo – 2026**

---

## Our Comunas

Our assigned comunas were **Peñaflor** and **Peñalolen**.

---

## The Anomaly

San Pedro registers an ENO notification rate of 609 cases per 10,000 inhabitants — 6.06 standard deviations above the regional mean — despite having only 11.3% foreign-born population and a near-zero educational gap. It is the only comuna out of 43 that exceeds the +2 SD threshold. Three independent checks (absolute case count, Poisson model residual, and GRD cross-check) converge on the same conclusion: the anomaly is not noise and is not explained by demographic variables. The most plausible explanation is a registration effect in the ENO notification system.

---

## Headline Figure

The headline figure (`headline.png`) is produced by `final_anomaly.ipynb`, Cell 6. Runtime is approximately 30 seconds on a standard laptop.

---

## How to Run

1. Clone the repository:  https://github.com/ICI-SofiaFV/IELE756-FinalProject
2. Install dependencies: pip install -r requirements.txt
3. Open the notebook: jupyter notebook final_anomaly.ipynb
4. Run all cells from top to bottom.

---

## Video

[Link to video](https://youtu.be/K2IFgJ8BCNQ)

---

## AI Use Disclosure

We used Claude (Anthropic) to assist with code debugging, structuring the `final_anomaly.ipynb` notebook, drafting Markdown explanations, and generating the video script. All analysis, interpretation, and conclusions were reviewed and validated by the team. We remain fully accountable for every line of code and every claim in this project.

---

## Data Sources

- **Census data:** Comuna-level demographic summary from Tarea 1
- **ENO data:** Notifiable disease notifications from Tarea 2  
- **GRD data:** Hospital discharge records from Tarea 2
- **Analytical table:** `tarea3_analytical_table.csv` — pre-computed master table from Tarea 3
