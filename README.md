<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f2027,50:203a43,100:2c5364&text=Krish%20Jain&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Machine%20Learning%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20Data%20Platforms&descAlignY=58&descSize=18&animation=fadeIn" alt="Krish Jain header" />
</p>

<p align="center">
  <a href="https://github.com/KrishJ13">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=4FD1C5&center=true&vCenter=true&width=640&lines=Final-year+BSc+Computer+Science+%26+AI+%40+Loughborough;Ex-ML+%26+Biological+Scientist+%40+MSD;Graph+Neural+Networks+for+Alzheimer's+research;Building+failure-tolerant+compute+schedulers;Turning+messy+data+into+decisions" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/krish-jain-734086226/"><img src="https://img.shields.io/badge/LinkedIn-Krish%20Jain-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:krish.s.jain@outlook.com"><img src="https://img.shields.io/badge/Email-krish.s.jain%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Based%20in-London%2C%20UK-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://komarev.com/ghpvc/?username=KrishJ13&style=for-the-badge&color=4FD1C5&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

### `$ whoami`

```python
class KrishJain:
    """ML engineer in the making. Likes hard problems, real data, and systems that don't fall over."""

    def __init__(self):
        self.location   = "London, UK"
        self.education  = "BSc Computer Science & Artificial Intelligence — Loughborough University (2023–2027)"
        self.experience = "ML & Biological Scientist, Industrial Placement — MSD (Jun 2025 – Jul 2026)"

        self.day_job    = ["machine learning", "graph neural networks", "survival analysis", "explainable AI"]
        self.night_job  = ["distributed systems", "streaming data platforms", "Kubernetes", "markets"]
        self.dream_job  = "robotics & embodied AI that genuinely helps people"

        self.currently  = {
            "building": "AcceleratorHub — a crash-proof GPU reservation & scheduling platform",
            "learning":  "Vision-Language-Action models, CUDA, and quant-style forecasting",
            "training":  "push / pull / cardio — the other kind of gradient descent 🏋️",
        }

    def ask_me_about(self):
        return ["GNNs on biological graphs", "EHR data at 500k-patient scale",
                "transactional outboxes", "why your first 3 results are probably leakage"]
```

---

### 🔭 Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ AcceleratorHub</h4>
      <sub><code>Java 21</code> <code>Spring Boot</code> <code>PostgreSQL</code> <code>Kubernetes</code> <code>Helm</code> <code>Argo CD</code></sub>
      <p>A multi-tenant <b>accelerator reservation & scheduling platform</b> built to survive crashes, retries and lost responses.</p>
      <ul>
        <li>Transactional outbox + idempotent ops for PostgreSQL → Kubernetes coordination</li>
        <li>Leases, fencing epochs and desired/observed reconciliation</li>
        <li>RBAC, namespace isolation & NetworkPolicy, negatively tested</li>
        <li>GitOps delivery with GitHub Actions, Helm & Argo CD; Grafana + tracing</li>
        <li>Scheduler benchmarked with JMH across concurrency strategies</li>
      </ul>
      <a href="https://github.com/KrishJ13/AcceleratorHub">→ View repo</a>
    </td>
    <td width="50%" valign="top">
      <h4>📈 MarketFlow</h4>
      <sub><code>Python</code> <code>Kafka</code> <code>PySpark</code> <code>Databricks</code> <code>Snowflake</code> <code>dbt</code> <code>Airflow</code></sub>
      <p>A <b>real-time financial data platform</b> — live market ticks to analyst-ready marts.</p>
      <ul>
        <li>Coinbase → Kafka → Delta Lake → Snowflake streaming pipeline</li>
        <li>Dimensional models (<code>fct_trade</code>, <code>fct_market_interval</code>) in dbt</li>
        <li>Airflow orchestration with reconciliation & quality gates</li>
        <li>p95 end-to-end freshness and Kafka lag monitored live</li>
        <li>CI controls validating correctness, not just “the job ran”</li>
      </ul>
      <a href="https://github.com/KrishJ13/MarketFlow">→ View repo</a>
    </td>
  </tr>
</table>

### 🧬 Industry experience

**ML & Biological Scientist — MSD (Merck Sharp & Dohme)** · *Industrial placement, Jun 2025 – Jul 2026*

- Re-engineered a published **multi-omics Graph Neural Network** for Alzheimer's research in PyTorch Geometric, with custom attention & message passing
- Unified **3 signalling-pathway knowledge bases** into one and applied transfer learning across cancer ↔ Alzheimer's
- Built longitudinal datasets for **500,000+ patients** spanning up to 90 years of electronic health records
- Survival analysis, clustering & explainable ML (SHAP, 5×2 CV) to shortlist **5 high-confidence candidate biomarkers**
- All under GDPR and strict data-governance controls; entered with zero biology background, left speaking it

---

### 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,pytorch,sklearn,tensorflow,spring,postgres,kubernetes,docker,kafka,aws,githubactions,grafana,linux,git,latex&perline=8" alt="Tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" />
  <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SHAP-explainable%20ML-555?style=flat-square" />
</p>

---

### 📊 GitHub in numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=KrishJ13&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KrishJ13&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=KrishJ13&theme=tokyonight&hide_border=true" alt="Contribution streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=KrishJ13&theme=tokyo-night&hide_border=true&area=true" alt="Activity graph" />
</p>

---

### 🎯 2026–27 roadmap

- [x] Ship a year of production-grade ML research at MSD
- [x] Build a fault-tolerant compute scheduler from scratch
- [x] Stream live market data into a governed lakehouse
- [ ] Final-year project on the frontier of embodied / trustworthy AI
- [ ] Win a hackathon on a real UK public-sector problem
- [ ] Land a Data & AI / ML engineering role for 2027

<details>
<summary><b>🎲 Fun facts (click me)</b></summary>
<br>

- Went from zero biology to finding Alzheimer's biomarker candidates in a year — graphs are graphs.
- Firm believer that a strong naive baseline is the most underrated model in ML.
- Trades on the side and sizes every position from the stop, not the leverage.
- Will happily talk about robots that help people until someone stops me.

</details>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:2c5364,50:203a43,100:0f2027&section=footer" alt="footer" />
</p>
