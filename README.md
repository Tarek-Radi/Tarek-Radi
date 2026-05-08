
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:0EA5E9,70:22C55E,100:111827&height=245&section=header&text=Tarek%20Mahmoud%20Abdelrady&fontSize=38&fontColor=F8FAFC&animation=fadeIn&fontAlignY=34&desc=Aspiring%20Data%20Engineer%20%7C%20Python%20%2B%20SQL%20%2B%20Azure%20%7C%20Egypt&descAlignY=55&descSize=16" alt="Tarek Mahmoud Abdelrady - Aspiring Data Engineer" />
</p>

<h1 align="center">Data Engineering Portfolio Console</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=700&color=38BDF8&center=true&vCenter=true&width=940&lines=Turning+raw+data+into+reliable+pipelines.;Designing+analytics-ready+warehouse+models.;Practicing+ETL%2FELT%2C+orchestration%2C+and+quality+checks.;Learning+Microsoft+Data+Engineering+with+Azure." alt="Typing headline for Tarek's data engineering focus" />
</p>

<p align="center">
  <a href="https://github.com/Tarek-Radi">
    <img src="https://img.shields.io/badge/GitHub-Tarek--Radi-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
  <a href="https://www.linkedin.com/in/tarek-mahmoud-abdelrady-404884354/">
    <img src="https://img.shields.io/badge/LinkedIn-Tarek%20Mahmoud%20Abdelrady-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="https://tarek-data-engineer-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Live%20Site-22C55E?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio site" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Tarek-Radi&style=for-the-badge&color=0EA5E9&label=PROFILE+VIEWS" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/Tarek-Radi?label=Followers&style=for-the-badge&logo=github&color=22C55E&labelColor=0D1117" alt="GitHub followers" />
  <img src="https://img.shields.io/badge/Based%20in-Egypt-F59E0B?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Based in Egypt" />
  <img src="https://img.shields.io/badge/Current%20Track-Azure%20Data%20Engineering-38BDF8?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure data engineering track" />
</p>

<p align="center">
  <a href="#portfolio-signal">
    <img src="https://img.shields.io/badge/Open-Portfolio%20Signal-0EA5E9?style=flat-square" alt="Portfolio signal navigation" />
  </a>
  <a href="#pipeline-map">
    <img src="https://img.shields.io/badge/View-Pipeline%20Map-22C55E?style=flat-square" alt="Pipeline map navigation" />
  </a>
  <a href="#data-engineering-toolbox">
    <img src="https://img.shields.io/badge/Inspect-Toolbox-F59E0B?style=flat-square" alt="Toolbox navigation" />
  </a>
  <a href="#featured-data-systems">
    <img src="https://img.shields.io/badge/Browse-Featured%20Projects-38BDF8?style=flat-square" alt="Featured projects navigation" />
  </a>
  <a href="#github-analytics">
    <img src="https://img.shields.io/badge/Read-GitHub%20Analytics-8B5CF6?style=flat-square" alt="GitHub analytics navigation" />
  </a>
</p>

---

## Portfolio Signal

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Identity-Aspiring%20Data%20Engineer-0EA5E9?style=flat-square" alt="Identity badge" />
      <br />
      <b>Pipeline Builder</b>
      <br />
      <sub>ETL/ELT, warehouse layers, repeatable workflows</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Education-Helwan%20University-22C55E?style=flat-square" alt="Helwan University badge" />
      <br />
      <b>Engineering Student</b>
      <br />
      <sub>Communications and Information Engineering</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Focus-Modern%20Data%20Stack-38BDF8?style=flat-square" alt="Modern data stack badge" />
      <br />
      <b>Analytics-Ready Data</b>
      <br />
      <sub>Data modeling, marts, tests, KPI layers</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/Learning-Microsoft%20Azure-F59E0B?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure learning badge" />
      <br />
      <b>Cloud Direction</b>
      <br />
      <sub>Cloud-ready architecture and Azure data services</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="55%" valign="top">
      <h3>About This Profile</h3>
      <p>
        I am <b>Tarek Mahmoud Abdelrady</b>, an aspiring Data Engineer based in Egypt. I am building a practical portfolio around production-like data systems: ingestion scripts, warehouse layers, orchestration, quality checks, dimensional models, and analytics-ready outputs.
      </p>
      <p>
        My current direction is <b>Microsoft Data Engineering with Azure</b>, supported by hands-on projects using <b>Python</b>, <b>SQL</b>, <b>PostgreSQL</b>, <b>SQL Server</b>, <b>Docker</b>, <b>Airflow</b>, <b>dbt</b>, <b>Pandas</b>, and clear technical documentation.
      </p>
    </td>
    <td width="45%" valign="top">
      <h3>Portfolio Query</h3>
      <pre><code>SELECT
  focus_area,
  project_signal,
  learning_track
FROM tarek_profile
WHERE role_target = 'Data Engineer'
  AND mindset = 'build reliable data systems';</code></pre>
      <p>
        <sub>Result: practical data engineering projects with clear architecture, repeatable workflows, and recruiter-readable documentation.</sub>
      </p>
    </td>
  </tr>
</table>

---

## Pipeline Map

```mermaid
flowchart LR
    A["Raw Sources<br/>CSV, JSONL, web data"] --> B["Ingestion<br/>Python, Pandas, SQL loads"]
    B --> C["Storage<br/>PostgreSQL, SQL Server"]
    C --> D["Transformation<br/>dbt, T-SQL, cleaning rules"]
    D --> E["Warehouse Layers<br/>Bronze, Silver, Gold"]
    E --> F["Analytics Models<br/>Facts, dimensions, KPIs"]
    F --> G["Business Questions<br/>Trends, performance, insights"]
```

<table>
  <tr>
    <td align="center" width="20%">
      <b>Raw</b>
      <br />
      <sub>Preserve source structure</sub>
    </td>
    <td align="center" width="20%">
      <b>Ingest</b>
      <br />
      <sub>Load data with Python or SQL</sub>
    </td>
    <td align="center" width="20%">
      <b>Transform</b>
      <br />
      <sub>Clean, cast, test, standardize</sub>
    </td>
    <td align="center" width="20%">
      <b>Model</b>
      <br />
      <sub>Facts, dimensions, marts</sub>
    </td>
    <td align="center" width="20%">
      <b>Analyze</b>
      <br />
      <sub>KPIs and BI-ready tables</sub>
    </td>
  </tr>
</table>

---

## Data Engineering Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,docker,azure,git,github,vscode&theme=dark" alt="Python, PostgreSQL, Docker, Azure, Git, GitHub, VS Code" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=databricks&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Apache Airflow" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
  <img src="https://img.shields.io/badge/DBeaver-382923?style=for-the-badge&logo=dbeaver&logoColor=white" alt="DBeaver" />
</p>

<table>
  <tr>
    <th align="left">Workspace</th>
    <th align="left">Tools</th>
    <th align="left">Portfolio Signal</th>
  </tr>
  <tr>
    <td><b>Ingestion</b></td>
    <td><code>Python</code>, <code>Pandas</code>, <code>Requests</code>, <code>BeautifulSoup</code>, <code>BULK INSERT</code></td>
    <td>Extract data, handle pagination, load CSV/JSONL, preserve raw schemas</td>
  </tr>
  <tr>
    <td><b>Warehouse</b></td>
    <td><code>PostgreSQL</code>, <code>SQL Server</code>, <code>DBeaver</code>, <code>SSMS</code></td>
    <td>Design relational structures, medallion layers, and analytical schemas</td>
  </tr>
  <tr>
    <td><b>Transformation</b></td>
    <td><code>SQL</code>, <code>T-SQL</code>, <code>dbt</code>, <code>Pandas</code></td>
    <td>Clean, standardize, type-cast, test, and model business-ready datasets</td>
  </tr>
  <tr>
    <td><b>Orchestration</b></td>
    <td><code>Airflow</code>, <code>Docker Compose</code>, <code>GitHub</code></td>
    <td>Run repeatable workflows with documented local setup and DAG execution</td>
  </tr>
  <tr>
    <td><b>Cloud Direction</b></td>
    <td><code>Azure</code>, <code>cloud data architecture</code></td>
    <td>Learn to move strong local data engineering fundamentals toward managed services</td>
  </tr>
</table>

---

## Featured Data Systems

<p align="center">
  <a href="https://github.com/Tarek-Radi/E-commerce-Data-Pipeline">
    <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=Tarek-Radi&repo=E-commerce-Data-Pipeline&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22C55E" alt="E-commerce Data Pipeline repository card" />
  </a>
  <a href="https://github.com/Tarek-Radi/solid-waste-data-warehouse">
    <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=Tarek-Radi&repo=solid-waste-data-warehouse&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22C55E" alt="Solid Waste Data Warehouse repository card" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Tarek-Radi/SQL-Data-Wearhouse-Project">
    <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=Tarek-Radi&repo=SQL-Data-Wearhouse-Project&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22C55E" alt="SQL Data Warehouse Project repository card" />
  </a>
  <a href="https://github.com/MohamedFathi201/LacosteeeTeam-repo">
    <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=MohamedFathi201&repo=LacosteeeTeam-repo&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22C55E" alt="Real-Time IoT Data Pipeline repository card" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Tarek-Radi/Wuzzuf-Job-Scraper">
    <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=Tarek-Radi&repo=Wuzzuf-Job-Scraper&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22C55E" alt="Wuzzuf Job Scraper repository card" />
  </a>
  <a href="https://github.com/Tarek-Radi/tarek-data-engineer-portfolio">
    <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=Tarek-Radi&repo=tarek-data-engineer-portfolio&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22C55E" alt="Data Engineer Portfolio repository card" />
  </a>
</p>

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">What It Demonstrates</th>
    <th align="left">Stack</th>
    <th align="left">Data Engineering Concepts</th>
  </tr>
  <tr>
    <td><a href="https://github.com/Tarek-Radi/E-commerce-Data-Pipeline"><b>E-commerce Data Pipeline</b></a></td>
    <td>End-to-end Olist e-commerce pipeline from raw CSVs to analytics-ready marts.</td>
    <td>Python, PostgreSQL, Docker, dbt, Airflow, Pandas, SQLAlchemy</td>
    <td>Raw/staging/marts, bronze/silver/gold, dbt tests, star schema, Airflow DAGs, KPI models</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Tarek-Radi/solid-waste-data-warehouse"><b>Solid Waste Data Warehouse</b></a></td>
    <td>SQL Server warehouse for solid waste collection analytics.</td>
    <td>SQL Server, T-SQL, CSV, stored procedures</td>
    <td>Medallion architecture, <code>BULK INSERT</code>, cleaning rules, star schema, <code>ROLLUP</code>, <code>CUBE</code>, <code>GROUPING SETS</code></td>
  </tr>
  <tr>
    <td><a href="https://github.com/Tarek-Radi/SQL-Data-Wearhouse-Project"><b>SQL Data Warehouse Project</b></a></td>
    <td>ERP and CRM source integration into a structured analytical warehouse.</td>
    <td>SQL Server, T-SQL, SSMS, Draw.io, Git</td>
    <td>ETL design, data cleaning, source integration, dimensional modeling, sales/customer/product analytics</td>
  </tr>
  <tr>
    <td><a href="https://github.com/MohamedFathi201/LacosteeeTeam-repo"><b>Real-Time IoT Data Pipeline</b></a></td>
    <td>Team project simulating car telemetry data with a roadmap for batch, streaming, alerts, and dashboards.</td>
    <td>Python, JSONL, Dockerfile, planned Azure tools, planned Kafka/Stream Analytics</td>
    <td>IoT-style event generation, state-machine simulation, streaming data shape, dashboard-ready telemetry</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Tarek-Radi/Wuzzuf-Job-Scraper"><b>Wuzzuf Job Scraper</b></a></td>
    <td>Structured extraction of job listings from Wuzzuf search pages into CSV.</td>
    <td>Python, Requests, BeautifulSoup, Pandas</td>
    <td>Web extraction, pagination, raw HTML parsing, cleaning, structured export, future scheduling/database loading</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Tarek-Radi/tarek-data-engineer-portfolio"><b>Data Engineer Portfolio</b></a></td>
    <td>Single-page portfolio website for presenting data engineering projects and direction.</td>
    <td>React, Vite, styled-components, Lucide React, Vercel</td>
    <td>Technical storytelling, recruiter-facing project presentation, documentation surface</td>
  </tr>
</table>

<details>
  <summary><b>Why these projects matter for recruiters</b></summary>
  <br />
  <table>
    <tr>
      <td><b>Pipeline thinking</b></td>
      <td>Projects are structured around source data, ingestion, transformation, storage, testing, and analytics output.</td>
    </tr>
    <tr>
      <td><b>Warehouse fundamentals</b></td>
      <td>Work includes medallion architecture, raw/staging/marts, facts, dimensions, and business-level KPI tables.</td>
    </tr>
    <tr>
      <td><b>Production-like habits</b></td>
      <td>Docker, Airflow, dbt, repository structure, README documentation, and local run instructions appear in the portfolio.</td>
    </tr>
    <tr>
      <td><b>Cloud readiness</b></td>
      <td>The learning path is moving toward Azure data engineering while keeping strong SQL and pipeline fundamentals.</td>
    </tr>
  </table>
</details>

---

## Current Build Board

<table>
  <tr>
    <th align="left">Now</th>
    <th align="left">Next</th>
    <th align="left">Later</th>
  </tr>
  <tr>
    <td valign="top">
      <b>Microsoft Data Engineering with Azure</b>
      <br />
      <sub>Learning core cloud data engineering concepts and Azure-style architecture.</sub>
    </td>
    <td valign="top">
      <b>More Pipeline Automation</b>
      <br />
      <sub>Deepen Airflow scheduling, dbt testing, and Dockerized workflow practice.</sub>
    </td>
    <td valign="top">
      <b>Cloud-Ready Portfolio Systems</b>
      <br />
      <sub>Move local patterns toward storage, orchestration, and analytics services in the cloud.</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Warehouse Modeling</b>
      <br />
      <sub>Strengthening facts, dimensions, grain, KPI tables, and business questions.</sub>
    </td>
    <td valign="top">
      <b>Data Quality Patterns</b>
      <br />
      <sub>Add clearer tests, validation rules, and project-level quality documentation.</sub>
    </td>
    <td valign="top">
      <b>BI and Analytics Outputs</b>
      <br />
      <sub>Expose more final models for reporting and dashboard use cases.</sub>
    </td>
  </tr>
</table>

## Learning Journey

```mermaid
flowchart LR
    A["SQL Foundations<br/>joins, aggregations, T-SQL"] --> B["Warehouse Design<br/>medallion architecture, star schema"]
    B --> C["Pipeline Engineering<br/>Python ingestion, Docker, Airflow"]
    C --> D["Analytics Engineering<br/>dbt models, tests, marts"]
    D --> E["Cloud Direction<br/>Microsoft Azure, cloud-ready systems"]
```

---

## GitHub Analytics

<p align="center">
  <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api?username=Tarek-Radi&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=22C55E&text_color=C9D1D9" alt="Tarek-Radi GitHub stats" />
  <img width="49%" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=Tarek-Radi&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9" alt="Tarek-Radi top languages" />
</p>

<p align="center">
  <img width="60%" src="https://github-readme-streak-stats.herokuapp.com/?user=Tarek-Radi&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=22C55E&currStreakLabel=38BDF8" alt="Tarek-Radi GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-profile-trophy.vercel.app/?username=Tarek-Radi&theme=algolia&no-frame=true&no-bg=true&margin-w=8&row=1&column=6" alt="Tarek-Radi GitHub trophy cards" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Tarek-Radi&theme=react-dark&hide_border=true&bg_color=0D1117&color=38BDF8&line=22C55E&point=FFFFFF&area=true&area_color=0EA5E9" alt="Tarek-Radi contribution graph" />
</p>

<p align="center">
  <sub>Language cards describe public repository code distribution. They do not measure overall skill level.</sub>
</p>

---

## Connect

<table align="center">
  <tr>
    <td align="center" width="33%">
      <a href="https://github.com/Tarek-Radi">
        <img src="https://img.shields.io/badge/GitHub-Explore%20Repositories-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="Explore GitHub repositories" />
      </a>
      <br />
      <sub>Project source code and documentation</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://www.linkedin.com/in/tarek-mahmoud-abdelrady-404884354/">
        <img src="https://img.shields.io/badge/LinkedIn-Professional%20Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
      </a>
      <br />
      <sub>Education, learning path, and professional updates</sub>
    </td>
    <td align="center" width="33%">
      <a href="https://tarek-data-engineer-portfolio.vercel.app/">
        <img src="https://img.shields.io/badge/Portfolio-View%20Live%20Site-22C55E?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio website" />
      </a>
      <br />
      <sub>Curated project presentation</sub>
    </td>
  </tr>
</table>

<p align="center">
  <b>Open to feedback, collaboration, and data engineering learning opportunities.</b>
  <br />
  <sub>Building practical, documented, cloud-ready data systems one project at a time.</sub>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,35:22C55E,70:0EA5E9,100:020617&height=120&section=footer" alt="Footer wave" />
</p>
