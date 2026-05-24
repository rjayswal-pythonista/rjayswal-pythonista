<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Roshan%20Jayswal&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Staff%20Software%20Engineer%20%7C%20Systems%20%7C%20Security%20%7C%20AI&descAlignY=55&descSize=18" width="100%"/>
</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&width=750&lines=8%2B+Years+%7C+Kernel+Datapath+%E2%86%92+Zero+Trust+%E2%86%92+AI+Agents;C%2FC%2B%2B+Linux+Kernel+%7C+TCP%2FIP+%7C+TLS%2FmTLS+%7C+ZPA;LangChain+%7C+LangGraph+%7C+MCP+%7C+RAG+Pipelines;Ex-Zscaler+Staff+SDE+%7C+Ex-Cisco+SE-III;BITS+Pilani+ME+9.13+CGPA+%F0%9F%8E%93)](https://git.io/typing-svg)

</div>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roshan-jayswal-ab4aa382/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://roshanjayswal-github-io.vercel.app)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:roshanjayswal15@gmail.com)
[![Phone](https://img.shields.io/badge/+91--9004117603-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+919004117603)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rjayswal-pythonista)

</div>

---

## 🧠 About Me

```cpp
class RoshanJayswal : public StaffSoftwareEngineer {
public:
    std::string location    = "Mumbai, India";
    std::string experience  = "8+ Years";
    std::string education   = "ME BITS Pilani (9.13 CGPA) | BE Fr.CRIT (80.50%)";

    std::vector<std::string> expertise = {
        "Kernel Datapath Engineering (C/C++)",
        "Zero Trust Network Security (ZPA)",
        "Distributed Systems & Microservices",
        "AI/ML — LangChain, LangGraph, MCP, RAG",
        "Linux Systems — POSIX, Multithreading, IPC",
        "TCP/IP · TLS/mTLS · BGP · IPsec · PPPoE"
    };

    std::vector<std::string> clients = {
        "Google", "Microsoft", "Vodafone",
        "Deutsche Bank", "SWISSCOM", "NTT",
        "US Military ($30M DLEP Program)"
    };

    std::string current_status = "Open to Senior/Staff SWE roles 🚀";
};
```

> *Staff SWE who has shipped production code deep in Linux kernel forwarding planes, tamed P0 crashes with GDB & TSan, built AI agents with LangGraph & MCP — and lived to tell the tale.*

---

## 💼 Work Experience

<table>
<tr>
<td width="50%" valign="top">

### 🔵 Zscaler *(Dec 2024 – Apr 2026)*
**Staff Software Development Engineer**
`C · C++ · Python · Linux · Distributed Systems · AI/ML`

- 🏗️ Led **SYNC PAUSE** feature — zero-downtime maintenance for global distributed DB tables across broker, wally & lookup
- 📊 Owned **ZPA Lookup Module** end-to-end: stats framework, Prometheus exporters, Grafana dashboards
- 🤖 Built **ZPA Core Bot** (Stacktrace Analyzer) — Gemini + Vertex AI Slack bot auto-correlating coredumps to Jira tickets
- 🔥 Resolved **P0/P1 crashes**: SIGSEGV race, ABBA deadlock, TLV buffer corruption, hash table corruption via GDB/TSan
- 🛡️ Hardened codebase: 10+ **Coverity CIDs**, SonarQube enforcement, ASAN OOM investigation
- 📈 Built **6-component Grafana dashboards** (Logical Partitioning, Lookup, LBB, TLS, Bootup Stats)

</td>
<td width="50%" valign="top">

### 🔵 Zscaler *(Sept 2023 – Nov 2024)*
**Senior Software Engineer II**
`C · C++ · Python · Linux · Cloud Security · Microservices`

- ⚡ Designed **L4 Proxy** service for Logical Partitioning — high-perf reverse proxy with SNI-based TLS routing at scale
- 🚀 Built **bootup stats framework** across broker, lookup, slogger, wally, np-gateway
- 🐛 Fixed P1 bugs (connection stats zero, LBB redirect flag); delivered LBB customer Grafana dashboards & alerts

### 🟡 Cisco Systems *(Feb 2021 – Sept 2023)*
**Software Engineer III**
`C · C++ · Python · Linux Kernel · TCP/IP · Routing`

- 🌐 **ASR1k kernel datapath** (IOS-XE) — PPPoE/ISG broadband for **Google, Microsoft, Vodafone, Deutsche Bank**
- 🎖️ Led **DLEP Protocol** (IPv6, QoS, Radio Routing) on C8Kv for **US Military — $30M program**; full PyATS automation suite
- Resolved **70+ customer-facing defects** in Multicast and SDWAN Service Chaining

### 🟡 Cisco Systems *(Aug 2018 – Feb 2021)*
**Software Engineer II**
`C · C++ · Linux Kernel · SDN · BGP · MPLS · NETCONF`

- 🔐 **TrustSec (CTS)** — hardware-enforced network segmentation; SDA-ACI dataplane integration
- 🔬 Designed **DPI hash algorithm** for EtherChannel kernel-level load balancing
- 📦 **NETCONF/ConfD/Yang** data modelling for controller-mode unification
- Fixed **80+ defects** in EtherChannel, CTS, MPLS TE-FRR kernel forwarding paths

</td>
</tr>
</table>

---

## 🚀 Key Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 ZPA Core Bot / Stacktrace Analyzer
AI-powered Slack bot using **Gemini CLI + Vertex AI** that auto-discovers and correlates Jira tickets from coredump/stacktraces. Drastically cut incident triage time for ZPA datapath P0/P1s.

`Gemini` `Vertex AI` `Slack API` `JIRA` `Python`

</td>
<td width="50%" valign="top">

### 🧪 AI-Powered Code Coverage & Risk Tool
Flask app + **GCP (BigQuery, AI Platform)** with real-time git diff analysis, Jenkins CI/CD integration, predictive quality metrics, and security risk scoring.

`Flask` `GCP` `BigQuery` `Jenkins` `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏗️ Enterprise RAG & Multi-Agent Systems
Production **RAG pipelines** (LangChain, LlamaIndex, Pinecone/FAISS); multi-agent systems with CrewAI, PydanticAI, AutoGen; **90+ n8n automation workflows** for business process automation.

`LangChain` `LlamaIndex` `CrewAI` `Pinecone` `FAISS` `n8n`

</td>
<td width="50%" valign="top">

### 🦙 LLM Fine-tuning & Deployment
Deployed **Llama, Mistral, DeepSeek** on AWS EC2/vLLM/Docker; **QLoRA fine-tuning** for domain adaptation; voice AI agents using Retell AI and ElevenLabs.

`vLLM` `QLoRA` `AWS EC2` `Docker` `Retell AI` `ElevenLabs`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-004482?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Systems & OS**

![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=flat-square&logo=linux&logoColor=black)
![POSIX](https://img.shields.io/badge/POSIX-FF6B35?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![LXC](https://img.shields.io/badge/LXC%2FKVM-333333?style=flat-square)
![GDB](https://img.shields.io/badge/GDB-A8323B?style=flat-square)
![TSan](https://img.shields.io/badge/TSan%2FASan-E34F26?style=flat-square)

**Networking & Security**

![TCP/IP](https://img.shields.io/badge/TCP%2FIP-005C99?style=flat-square)
![TLS](https://img.shields.io/badge/TLS%2FmTLS-FF6B6B?style=flat-square)
![Zero Trust](https://img.shields.io/badge/Zero%20Trust-6C3483?style=flat-square)
![BGP](https://img.shields.io/badge/BGP%2FOSPF%2FMPLS-2E86AB?style=flat-square)
![IPsec](https://img.shields.io/badge/IPsec%2FVpn-1A535C?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![DPI](https://img.shields.io/badge/DPI%2FFirewall-C62828?style=flat-square)

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-8B5CF6?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-F59E0B?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7B2FBE?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4088?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)

**Backend & Infra**

![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=black)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

</div>

---

## 📂 Repositories

### 🤖 AI / LLM — Courses & Projects

| Repository | What's Inside | Tech |
|---|---|---|
| [**langchain-course**](https://github.com/rjayswal-pythonista/langchain-course) | Complete LangChain course — chains, agents, memory, RAG, tools, real-world projects | `Python` `LangChain` `OpenAI` |
| [**langgraph-course**](https://github.com/rjayswal-pythonista/langgraph-course) | LangGraph — stateful agents, ReAct, Reflexion, RAG agents, agentic workflows | `Python` `LangGraph` |
| [**mcp-crash-course**](https://github.com/rjayswal-pythonista/mcp-crash-course) | Model Context Protocol — FastMCP, Docker MCP, SSE, resources, prompts | `Python` `MCP` `FastMCP` |

### 🏗️ System Design

| Repository | What's Inside |
|---|---|
| [**system-design**](https://github.com/rjayswal-pythonista/system-design) | Scalable systems at scale — HLD patterns, distributed systems, interview prep |
| [**system-design-primer**](https://github.com/rjayswal-pythonista/system-design-primer) | Design large-scale systems — Anki flashcards included |
| [**awesome-system-design**](https://github.com/rjayswal-pythonista/awesome-system-design) | Curated list of Distributed Systems resources |
| [**navigating-system-design**](https://github.com/rjayswal-pythonista/navigating-system-design) | System design navigation guide and reference architectures |
| [**low-level-design-primer**](https://github.com/rjayswal-pythonista/low-level-design-primer) | LLD — OOP design patterns, SOLID, design interview prep |
| [**grokking-the-object-oriented-design-interview**](https://github.com/rjayswal-pythonista/grokking-the-object-oriented-design-interview) | OOD interview prep — class diagrams, patterns, real-world systems |

### 🧠 Data Structures & Algorithms

| Repository | Lang |
|---|---|
| [**Algorithms**](https://github.com/rjayswal-pythonista/Algorithms) — Stanford Algorithms Specialization | `Python` |
| [**DSA_CPP**](https://github.com/rjayswal-pythonista/DSA_CPP) — Personal DSA practice | `C++` |
| [**DSA_Python**](https://github.com/rjayswal-pythonista/DSA_Python) — DSA in Python ⭐ | `Python` |
| [**DSA_C**](https://github.com/rjayswal-pythonista/DSA_C) — DSA in C | `C` |
| [**Dynamic-Programming**](https://github.com/rjayswal-pythonista/Dynamic-Programming) — DP patterns | — |
| [**Graph-Coding-Minutes**](https://github.com/rjayswal-pythonista/Graph-Coding-Minutes) — Graph algorithms | — |
| [**data-structures-algorithms-level-up-bootcamp**](https://github.com/rjayswal-pythonista/data-structures-algorithms-level-up-bootcamp) — Level up DSA | `C++` |
| [**graph-algorithms-for-competitive-coding**](https://github.com/rjayswal-pythonista/graph-algorithms-for-competitive-coding) — Competitive programming graphs | — |

### 💻 LeetCode

| Repository | Description |
|---|---|
| [**LeetCode-Solutions**](https://github.com/rjayswal-pythonista/LeetCode-Solutions) | Python / Modern C++ — 1950+ problems |
| [**LeetCode-Questions-CompanyWise**](https://github.com/rjayswal-pythonista/LeetCode-Questions-CompanyWise) | Company-wise sorted by frequency |
| [**leetcode_company_wise_questions**](https://github.com/rjayswal-pythonista/leetcode_company_wise_questions) | LeetCode premium company-wise list |
| [**Ref1_LeetCode**](https://github.com/rjayswal-pythonista/Ref1_LeetCode) | All solved LeetCode problems |
| [**LeetCode-1**](https://github.com/rjayswal-pythonista/LeetCode-1) | Coding interview question collection |
| [**Leetcode**](https://github.com/rjayswal-pythonista/Leetcode) | LeetCode solutions in Python 🎓 |

### 🐍 Python

| Repository | Description |
|---|---|
| [**Python**](https://github.com/rjayswal-pythonista/Python) | All algorithms in Python ⭐ |
| [**OOP_Python**](https://github.com/rjayswal-pythonista/OOP_Python) | Object-Oriented Programming ⭐ |
| [**DS_indepth_python**](https://github.com/rjayswal-pythonista/DS_indepth_python) | Deep dive into Python data structures ⭐ |
| [**python-reference**](https://github.com/rjayswal-pythonista/python-reference) | Python Quick Reference ⭐ |
| [**Python-for-Algorithms--Data-Structures--and-Interviews**](https://github.com/rjayswal-pythonista/Python-for-Algorithms--Data-Structures--and-Interviews) | Udemy — Python for DSA & Interviews ⭐ |
| [**Book_on_Python_Algorithms_and_Data_Structure**](https://github.com/rjayswal-pythonista/Book_on_Python_Algorithms_and_Data_Structure) | Book on Python, Algorithms & Data Structures ⭐ |
| [**python-web-scraping**](https://github.com/rjayswal-pythonista/python-web-scraping) | Simple web scraping programs |

### ⚙️ Systems Programming — C / C++

| Repository | Description | Lang |
|---|---|---|
| [**C**](https://github.com/rjayswal-pythonista/C) | All algorithms in C ⭐ | `C` |
| [**C-Plus-Plus**](https://github.com/rjayswal-pythonista/C-Plus-Plus) | All algorithms in C++ | `C++` |
| [**C_Multithreading**](https://github.com/rjayswal-pythonista/C_Multithreading) | pthreads, synchronization, concurrency | `C` |
| [**CPP_Multithreading**](https://github.com/rjayswal-pythonista/CPP_Multithreading) | std::thread, mutex, condition variables | `C++` |
| [**Modern_CPP_Multithreading**](https://github.com/rjayswal-pythonista/Modern_CPP_Multithreading) | C++17/20 concurrency patterns | `C++` |
| [**linux**](https://github.com/rjayswal-pythonista/linux) | Linux kernel source tree | — |

### 🌐 Web & Portfolio

| Repository | Description |
|---|---|
| [**roshanjayswal-github-io.vercel.app**](https://roshanjayswal-github-io.vercel.app) | 🌐 Personal portfolio website |
| [**fullstack-course4**](https://github.com/rjayswal-pythonista/fullstack-course4) | HTML, CSS & JavaScript — Web Developers (Coursera) |
| [**html_css**](https://github.com/rjayswal-pythonista/html_css) | HTML & CSS projects |

---

## 🎓 Education & Certifications

<table>
<tr>
<td width="50%" valign="top">

### 🎓 Education

| Degree | Institution | Score |
|---|---|---|
| **ME — Communication Engineering** | BITS Pilani | **CGPA 9.13/10** |
| **BE — Electronics & Telecom** | Fr. CRIT, Mumbai | **80.50%** |

</td>
<td width="50%" valign="top">

### 🏅 Awards & Publications

- 🥈 **1st Runner-Up** — HackFest2k19 (Cisco)
- 🏆 **Narotam Sekhsaria Scholarship**
- 🌟 **L&T Outstanding Academic Performance**
- 📄 FPGA Based Alarm Module — *ICIEEE-2015*
- 📄 Patient Health Monitoring via IoT — *IEEE ICIIP-2017*

</td>
</tr>
</table>

### 📜 Certifications

![GenAI](https://img.shields.io/badge/Mastering_GenAI_%26_LLMs-Ed_Donner_Udemy-FF6B6B?style=flat-square)
![LangGraph](https://img.shields.io/badge/AI_Agents_LangChain%2FLangGraph-Udemy-1C3C3C?style=flat-square)
![n8n](https://img.shields.io/badge/Complete_n8n_AI_Automation-Udemy-EA4B71?style=flat-square)
![Stanford](https://img.shields.io/badge/Algorithm_Specialization-Stanford%2FCoursera-8B0000?style=flat-square)
![Cisco](https://img.shields.io/badge/Security_Ninja_Green_Belt-Cisco-1BA0D7?style=flat-square)
![Coursera](https://img.shields.io/badge/AI_for_Everyone-Coursera-0056D2?style=flat-square)
![HackerRank](https://img.shields.io/badge/Problem_Solving_Intermediate-HackerRank-2EC866?style=flat-square)

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=rjayswal-pythonista&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117"/>
&nbsp;
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rjayswal-pythonista&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=rjayswal-pythonista&theme=tokyonight&hide_border=true&background=0D1117)](https://git.io/streak-stats)

</div>

---

## 📬 Contact

<div align="center">

| | |
|:---:|:---|
| 📧 | [roshanjayswal15@gmail.com](mailto:roshanjayswal15@gmail.com) |
| 📱 | [+91 9004117603](tel:+919004117603) |
| 💼 | [linkedin.com/in/roshan-jayswal-ab4aa382](https://www.linkedin.com/in/roshan-jayswal-ab4aa382/) |
| 🌐 | [roshanjayswal-github-io.vercel.app](https://roshanjayswal-github-io.vercel.app) |
| 📍 | Mumbai, Maharashtra, India |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

![Visitor Count](https://komarev.com/ghpvc/?username=rjayswal-pythonista&color=00D9FF&style=flat-square&label=Profile+Views)

</div>
