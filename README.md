<!-- HEADER (animated wave) -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:F78C6C,100:C792EA&height=220&section=header&text=Brian%20Gerard&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Computer%20Engineer%20%7C%20Virtualization%20Engineer&descAlignY=58&descSize=20" alt="Brian Gerard header" />
</p>

<h1 align="center">Hi, I'm Brian Gerard 👋👨‍💻</h1>
<h3 align="center">Computer Engineer 🎓 | Virtualization Engineer</h3>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=F78C6C&center=true&vCenter=true&width=650&lines=Computer+Engineer+%40+UNC+%F0%9F%8E%93;Virtualization+Engineer+%40+Alsus+AR;IaC+%7C+Ansible+%26+Terraform;Security+Automation+%26+GitOps;Kubernetes,+RabbitMQ+%26+Elasticsearch" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=brian1062&color=orange&style=for-the-badge" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Computer_Engineer-UNC-F78C6C?style=for-the-badge&logo=academia&logoColor=white" alt="Computer Engineer" />
  <img src="https://img.shields.io/badge/Based_in-Córdoba,_AR_🇦🇷-1f6feb?style=for-the-badge" alt="Location" />
</p>

---

### 👨‍💻 About Me

I am a **Computer Engineer** graduated from the National University of Córdoba (UNC), working on cloud infrastructure, automation, and virtualized environments, with a strong background spanning from low-level hardware design to cloud-native architectures.

- 🚀 **Current Role:** Virtualization Engineer at **Alsus AR** (Ansible, Terraform, and Elastic Stack).
- 🎓 **Engineering Thesis:** Co-developed an automated SOC platform for network incident response using Suricata, RabbitMQ, Argo Events (K3s), FastMCP (LLMs), and AWX.
- ⚙️ **Previous Experience:** 1 year as **DevOps Engineer** at *Prosecretaría de Informática - UNC* (Kubernetes & microservices orchestration).
- 🔬 **R&D & Training:** 1 year as a **Procom Fellow (Training Grant)** at *Fundación Fulgor*, developing a complete **Real-Time Video Processing system**: DSP algorithms on FPGAs with Verilog, microcontrollers, and web interfaces.
- 📍 **Location:** Córdoba, Argentina 🇦🇷

---

### 🛣️ Journey

| Period | Milestone |
| :--- | :--- |
| **Now** | 🚀 Virtualization Engineer @ **Alsus AR** |
| **Now** | 🎓 **Computer Engineer** — Universidad Nacional de Córdoba (UNC) |
| **Previous** | ⚙️ DevOps Engineer @ Prosecretaría de Informática - UNC (1 year) |
| **Previous** | 🔬 Procom Fellow @ Fundación Fulgor (1 year) |

---

### 🛠️ Tech Stack & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,linux,ansible,terraform,githubactions,rabbitmq,elasticsearch,python,fastapi,c&perline=11" alt="Skill icons" />
</p>

| Category | Technologies |
| :--- | :--- |
| **Virtualization & Containers** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| **IaC & Automation** | ![Ansible](https://img.shields.io/badge/Ansible-E00A00?style=for-the-badge&logo=ansible&logoColor=white) ![AWX](https://img.shields.io/badge/AWX-000000?style=for-the-badge&logo=ansible&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![HCP Terraform](https://img.shields.io/badge/HCP_Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=black) |
| **Messaging & Event-Driven** | ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Argo](https://img.shields.io/badge/Argo_Events-EF7B4D?style=for-the-badge&logo=argo&logoColor=white) |
| **Observability & Security** | ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) ![Suricata](https://img.shields.io/badge/Suricata_IDS-EF3B2D?style=for-the-badge) ![Fortinet](https://img.shields.io/badge/Fortinet-C8102E?style=for-the-badge&logo=fortinet&logoColor=white) |
| **Backend & Development** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) |
| **Embedded & Hardware** | ![Verilog](https://img.shields.io/badge/Verilog-2C2255?style=for-the-badge) ![FPGA](https://img.shields.io/badge/FPGA-005571?style=for-the-badge) ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) |

---

### 🎓 Engineering Thesis

Together with a colleague, we designed and implemented an end-to-end **Autonomous Operations Pipeline** to bridge the gap between passive observability and active threat remediation.

- **Event Pipeline:** Suricata IDS telemetry is ingested and routed asynchronously via RabbitMQ and Argo Events inside a K3s cluster.
- **Cognitive Decision Layer:** A FastMCP server interfaces with an LLM to evaluate complex incident context.
- **Remediation as Code:** Remediation playbooks are dynamically triggered in AWX via FortiOS REST APIs under a supervised *Human-in-the-Loop* approval model.

<details>
<summary><b>🧭 View architecture</b></summary>
<br>

```mermaid
flowchart LR
    A[Suricata IDS] -->|alerts| B[RabbitMQ]
    B --> C[Argo Events<br/>K3s]
    C --> D[FastMCP + LLM<br/>incident analysis]
    D --> E{Human-in-the-Loop<br/>approval}
    E -->|approved| F[AWX playbook]
    F --> G[FortiOS REST API]
    E -->|rejected| H[(Audit log)]
```

</details>

---

### 📈 GitHub Activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=brian1062&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=brian1062&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=brian1062&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=brian1062&theme=tokyo-night&hide_border=true&area=true&color=F78C6C&line=C792EA&point=ffffff" alt="Contribution graph" />
</p>

<!-- Snake animation: generated by .github/workflows/snake.yml (branch "output") -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/brian1062/brian1062/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/brian1062/brian1062/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/brian1062/brian1062/output/github-snake.svg" />
  </picture>
</p>

---

### 🌐 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/brian-gerard-143803261/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:bgerard1062@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
  <a href="https://twitter.com/brian_gerard"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/></a>
  <a href="https://www.instagram.com/brian.gerard"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
</p>

<!-- FOOTER (animated wave) -->
<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:C792EA,100:F78C6C&height=120&section=footer" alt="footer" />
</p>
