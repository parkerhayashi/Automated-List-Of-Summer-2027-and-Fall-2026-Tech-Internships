<div align="center">

# 🍁 Canada, Japan & more Tech Internships

**A self-updating engine that tracks tech internships so you don't have to.**

[![CI](https://img.shields.io/github/actions/workflow/status/parkerhayashi/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/ci.yml?branch=main&label=tests&style=flat-square&color=3fb950)](https://github.com/parkerhayashi/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/actions/workflows/ci.yml)&nbsp;[![Open roles](https://img.shields.io/badge/dynamic/json?label=open%20roles&query=open_total&url=https%3A%2F%2Fparkerhayashi.github.io%2FAutomated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships%2Fapi%2Fstats.json&color=2f81f7&style=flat-square)](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/)&nbsp;![Updates](https://img.shields.io/badge/updates-every%2030%20min-3fb950?style=flat-square)&nbsp;[![RSS](https://img.shields.io/badge/RSS-subscribe-e67e22?style=flat-square)](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/feed.xml)

### 267 open roles (207 listed below) · 196 new this week

4,629 employers tracked · data as of Sep 25, 2026 at 01:02 UTC

_108 have a cycle the employer stated · 159 are recent postings whose cycle isn't stated (listed separately, never mixed in)._

**[🖥️ Live dashboard](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/)** · **[📡 RSS](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/feed.xml)** · **[⚙️ JSON API](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/api/jobs.json)**

</div>

> [!TIP]
> **⭐ Star this repo** to save it and get updates when new roles are added.

Instead of refreshing a dozen career pages by hand, it reads company hiring feeds directly and keeps one live list — newest roles on top, refreshed automatically throughout the day.

**🔔 New roles in your inbox:** [RSS](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/feed.xml) or [Feedrabbit](https://feedrabbit.com/subscriptions/new?url=https%3A%2F%2Fraw.githubusercontent.com%2Fparkerhayashi%2FAutomated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships%2Fmain%2Fdocs%2Ffeed.xml).

---

## What this is

This is an engine, not a hand-kept list. It polls company career feeds every 30 minutes, finds the internships, removes duplicates, and rebuilds this page on its own.

Every link comes straight from the source — so it's real and current, not a stale list someone forgot to update. Speed matters.

## What makes this different

| | |
|---|---|
| 📅 **[Drop Radar](#drop-radar)** | A forecast of **what's coming**. Each marquee company's typical opening window, replaced by the real drop date the moment the engine catches it live. Windows are estimates and labelled as such; only dates the engine saw itself are marked verified. |
| 🛂 **Work authorization, from the posting** | 🇨🇦 / 🇯🇵 / 🛂 flags detected automatically from every job description — citizenship required, or the employer says it won't sponsor a work permit. Most postings say nothing either way, and those show as unknown rather than guessed. |
| 📆 **A real date on nearly every role** | Taken from the job portal itself wherever the portal states one, so newest-first actually means newest. The exact coverage figure is printed at the bottom of this page every run. |
| 🧰 **Skill tags + pay, extracted** | Every posting's text is scanned for the stack it wants (Python, C++, PyTorch, …) and the pay it states — searchable on the [dashboard](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/), and included in the CSV and API. |
| 🔔 **Alerts your way** | [RSS](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/feed.xml) — point any reader, or a Slack/Discord RSS integration, at it. Plus a [live dashboard](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/) with search, filters, and a saved-roles list that never leaves your browser. |
| ⚙️ **An engine, not a spreadsheet** | 4,891 job-board endpoints (4,629 distinct employers; some run more than one board) polled every 30 minutes across 12 ATS platforms. Full source and tests in this repo. |

## Scope

| | |
|---|---|
| **Roles** | Software, Data & ML/AI, Quant, Product (PM / TPM), VC, and Product Design / UX internships — not marketing, recruiting, or general business |
| **Region** | Canada, Japan, Australia, Austria, Chile, Costa Rica, Croatia, Czech Republic, Estonia, France, Germany, Greece, Ireland, Italy, Latvia, Lithuania, Luxembourg, Norway, Poland, Portugal, Slovakia, Slovenia, Spain, Sweden, Switzerland, Taiwan, and United Kingdom |
| **Cycles** | Summer 2027 |

## About

This fork of the internship engine tracks software, data, ML, quant, product (PM/TPM), venture capital, and product-design internships and co-ops located in Canada, Japan, and 25 other countries for Summer 2027, plus recent postings that don't name a cycle. The Scope table lists every country.

Use it to spot roles early and apply before they fill up. Being first genuinely helps.

## Where this is going

I'm building this in the open and adding to it as it grows.

**Recently shipped:** the Drop Radar · auto-detected sponsorship flags · the live dashboard

**Next up:** personalized alerts (pick your categories) · per-company hiring pages · a ghost-posting detector

If it helps you, a star means a lot and tells me to keep going.

## How to use

<details>
<summary><b>Reading the table — flags, dates, and the cycle split</b> (click to expand)</summary>

- Roles are grouped by **region** (Canada, then Japan, then IEC countries), then by cycle - **newest posting on top, oldest at the bottom.**
- A cycle section holds only roles whose **employer stated that cycle** - in the title, or in the posting's own text. Postings that name no cycle anywhere are in *Recently posted — cycle not stated* under the same region, with **no cycle guessed for them**. Same quality bar, different amount of evidence.
- The **Posted** column is the date the company published the role.
- **_(3 openings)_ after a role title** = the employer has that many separate live requisitions for the same job, in the same place, for the same cycle. They're all real and each takes its own application, so they're linked individually (**Apply**, then **#2**, **#3**) instead of repeating the row. Counts still count requisitions, and the CSV export is never grouped.
- **🆁 after a company name** = **this role is remote** — the posting's own location or title says so. It marks the role on that row, not the whole company.
- **Flags after a role title:** 🇨🇦 = requires Canadian citizenship, permanent residency, or a security clearance · 🇯🇵 = requires Japanese citizenship or nationality · 🛂 = the posting says it won't sponsor a work permit · 🆕 = spotted in the last 48 hours. Sponsorship flags are detected automatically from each job description - treat them as a strong hint and confirm on the posting.

- Track your applications with [`data/internships.csv`](data/internships.csv) (opens in Excel / Google Sheets).
- Missing a company? Adding one takes a single line, see [CONTRIBUTING.md](CONTRIBUTING.md).

</details>

---

**Jump to:** [Canada](#canada) · [Japan](#japan) · [IEC countries](#iec)

<a id="canada"></a>
## Summer 2027 — Canada  (27 employer-stated)

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Semtech | Firmware Design Intern 🆕 | Hardware | CAN - Ottawa, ON | Python, C++ | Sep 24, 2026 | [Apply](https://semtech.wd1.myworkdayjobs.com/SemtechCareers/job/CAN---Ottawa-ON/Firmware-Design-Intern_REQ3617) |
| Amazon | Software Development Engineer Intern - Summer 2027 (CAN) | Software | Vancouver, International | Python, Java, C++, C# | Sep 18, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10553947/software-development-engineer-intern-summer-2027-can) |
| Tower Research Capital | Stagiaire en développement de logiciels (été 2027) / Software Developer Intern (Summer 2027) | Software | Montreal | Python, Java, C++, Go | Sep 17, 2026 | [Apply](https://www.tower-research.com/open-positions/?gh_jid=8212179) |
| Manulife Financial | Summer Intern 2027 - Software Engineering (12 Months) | Software | Waterloo, Ontario | Python, Java, JavaScript, HTML/CSS | Sep 17, 2026 | [Apply](https://manulife.wd3.myworkdayjobs.com/MFCJH_Jobs/job/Waterloo-Ontario/Summer-Intern-2027---Software-Engineering--12-Months-_JR26091053) |
| Manulife Financial | Summer Intern 2027 - Infrastructure Equity Internship | Software | Toronto, Ontario | HTML/CSS | Sep 17, 2026 | [Apply](https://manulife.wd3.myworkdayjobs.com/MFCJH_Jobs/job/Toronto-Ontario/Summer-Intern-2027---Infrastructure-Equity-Internship_JR26081107) |
| British Columbia Investment | AI and Automation Engineer Co-op/Internship (Winter & Summer 2027) | Data & ML/AI | Victoria, BC | Python, LLMs, Azure, Terraform | Sep 17, 2026 | [Apply](https://bci.wd10.myworkdayjobs.com/BCI_Careers/job/Victoria-BC/AI-and-Automation-Engineer-Co-op-Internship--Winter---Summer-2027-_JR101597-1) |
| British Columbia Investment | DevSecOps Engineer Co-op/Internship (Winter 2027 & Summer 2027) | Software | Victoria, BC | No skills listed | Sep 17, 2026 | [Apply](https://bci.wd10.myworkdayjobs.com/BCI_Careers/job/Victoria-BC/DevSecOps-Engineer-Co-op-Internship--Winter-2027---Summer-2027-_JR101591) |
| British Columbia Investment | Investment Tech/Data & Analytics -  Software Engineer Co-op Internship (Winter 2027 or Winter & Summer 2027) | Data & ML/AI | Victoria, BC | Git | Sep 17, 2026 | [Apply](https://bci.wd10.myworkdayjobs.com/BCI_Careers/job/Victoria-BC/Investment-Tech-Data---Analytics----Software-Engineer-Co-op-Internship--Winter-2027-or-Winter---Summer-2027-_JR101596) |
| DoorDash | Software Engineer, Intern (Summer 2027) - TOR | Software | Toronto, ON | Python, Java, SQL, Kotlin | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/doordashcanada/jobs/8170944) |
| Royal Bank of Canada | 2027 Capital Markets, Global Equities, AI Engineer (16 Months, Co-op) | Data & ML/AI | TORONTO, Ontario, Canada | Python, PyTorch, scikit-learn, Pandas | Sep 14, 2026 | [Apply](https://rbc.wd3.myworkdayjobs.com/RBCEARLYTALENT1/job/TORONTO-Ontario-Canada/XMLNAME-2027-Capital-Markets--Global-Equities--AI-Engineer--16-Months--Co-op-_R-0000187401-1) |
| Royal Bank of Canada | 2027 Capital Markets, Global Equities, Algorithmic Trading Developer (16 Months, Co-op) | Quant | TORONTO, Ontario, Canada | Python, Java, C++, Linux | Sep 14, 2026 | [Apply](https://rbc.wd3.myworkdayjobs.com/RBCEARLYTALENT1/job/TORONTO-Ontario-Canada/XMLNAME-2027-Capital-Markets--Global-Equities--Algorithmic-Trading-Developer--16-Months--Co-op-_R-0000187792) |
| Royal Bank of Canada | 2027 Capital Markets, Global Equities, Quantitative Trading Analyst (16 Months, Co-op) | Quant | TORONTO, Ontario, Canada | Python, SQL | Sep 14, 2026 | [Apply](https://rbc.wd3.myworkdayjobs.com/RBCEARLYTALENT1/job/TORONTO-Ontario-Canada/XMLNAME-2027-Capital-Markets--Global-Equities--Quantitative-Trading-Analyst--16-Months--Co-op-_R-0000187742) |
| Bank of Montreal | Quantitative Developer (Alpha Research Team) - GAM, Summer 2027 (Co-op/Internship) - 12 months | Quant | Toronto, ON, CAN | Python, SQL, Pandas, AWS | Sep 14, 2026 | [Apply](https://bmo.wd3.myworkdayjobs.com/External/job/Toronto-ON-CAN/Quantitative-Developer--Alpha-Research-Team----GAM--Summer-2027--Co-op-Internship----12-months_R260026715-3) |
| Robinhood | Software Developer Intern, Backend (Summer 2027) | Software | Toronto, Canada | Python, Django, AWS, Kubernetes | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/robinhood/jobs/8142930?t=gh_src=&gh_jid=8142930) |
| Robinhood | Software Developer Intern, iOS (Summer 2027) | Software | Toronto, Canada | Swift | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/robinhood/jobs/8199729?t=gh_src=&gh_jid=8199729) |
| Robinhood | Software Developer Intern, Web (Summer 2027) | Software | Toronto, Canada | Python, TypeScript, JavaScript, React | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/robinhood/jobs/8199744?t=gh_src=&gh_jid=8199744) |
| Amazon | ML Systems Software Development Engineer Intern, Annapurna Labs - 2027 | Data & ML/AI | Toronto, International | Python, C++, TypeScript, PyTorch | Sep 11, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10538066/ml-systems-software-development-engineer-intern-annapurna-labs-2027) |
| Lyft | UX Research Intern (Summer 2027) | Design | Toronto, Canada | SQL | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8797069002?gh_jid=8797069002) |
| Lyft | Software Engineer Intern, Machine Learning (Summer 2027 - Toronto) | Data & ML/AI | Toronto, Canada | Python, PyTorch, TensorFlow, scikit-learn | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8802332002?gh_jid=8802332002) |
| Lyft | Software Engineer Intern, Test Automation (Summer 2027) | Software | Montreal, Canada | No skills listed | Sep 11, 2026 | [Apply](https://app.careerpuck.com/job-board/lyft/job/8767534002?gh_jid=8767534002) |
| Amazon | Software Development Engineer Intern, ROBOTICS - 2027 | Hardware | Toronto, International | Python, Java, C++, C# | Sep 09, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10535280/software-development-engineer-intern-robotics-2027) |
| PricewaterhouseCoopers (PwC) | May 2027 - Cyber as a Service - Summer Intern - Ottawa | Security | Ottawa | Python, Java, C++, HTML/CSS | Sep 04, 2026 | [Apply](https://pwc.wd3.myworkdayjobs.com/Global_Campus_Careers/job/Ottawa/May-2027---Cyber-as-a-Service---Summer-Intern---Ottawa_759780WD) |
| TC Energy | Student Intern, Computer Science | Software | Calgary, Alberta | No skills listed | Sep 01, 2026 | [Apply](https://tcenergy.wd3.myworkdayjobs.com/CAREER_SITE_TC/job/Calgary-Alberta/Student-Intern--Computer-Science_JR-10733) |
| Manulife Financial | Summer Intern 2027 - AI | Data & ML/AI | Toronto, Ontario | Python, Java, SQL, PyTorch | Aug 31, 2026 | [Apply](https://manulife.wd3.myworkdayjobs.com/MFCJH_Jobs/job/Toronto-Ontario/Summer-Intern-2027---AI_JR26081688) |
| Lumentum | Software Verification Engineer (Co-op/Intern) _(2 openings)_ | Software | Canada - Ottawa (Bill Leathem) | Python, C#, Bash, Linux | Aug 28, 2026 | [Apply](https://lumentum.wd5.myworkdayjobs.com/LITE/job/Canada---Ottawa-Bill-Leathem/Software-Verification-Engineer--Co-op-Intern-_20261135) [#2](https://lumentum.wd5.myworkdayjobs.com/LITE/job/Canada---Ottawa-Bill-Leathem/Software-Verification-Engineer--Co-op-Intern-_20261136) |
| Georgian Partners Growth | AI/ML Engineer Intern (2027) | Data & ML/AI | Toronto Headquarters | Python, PyTorch, TensorFlow, scikit-learn | Jul 14, 2026 | [Apply](https://jobs.ashbyhq.com/georgian/2ae71a4b-dd9d-4068-8ef2-81351ee74cab) |
| Squarepoint Capital | Intern Software Developer - Montreal - 2027 | Software | Montreal | Python, Java, C++, Rust | May 07, 2026 | [Apply](https://www.squarepoint-capital.com/open-opportunities?id=7905463&gh_jid=7905463) |

## Recently posted — cycle not stated — Canada  (30 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Entrust | Intern, Software Development - Hybrid in Ottawa 🆕 | Software | Canada - Ottawa | C#, React, .NET, Git | Sep 23, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/Canada---Ottawa/Intern--Software-Development---Hybrid-in-Ottawa_R004360) |
| Entrust | Intern – Software Development  - 8 months - Hybrid Ottawa 🆕 | Software | Canada - Ottawa | Java, TypeScript, JavaScript, React | Sep 23, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/Canada---Ottawa/XMLNAME--Intern---Software-Development----8-months---Hybrid-Ottawa_R004359) |
| CIBC | Application/Software Developer Co-op | Software | Toronto, ON | Python, Azure, Databricks | Sep 22, 2026 | [Apply](https://cibc.wd3.myworkdayjobs.com/campus/job/Toronto-ON/Application-Software-Developer-Co-op_2619454) |
| Marvell | Firmware Engineer Intern | Hardware | CA-ON - Toronto - TOR | Python, C++, LLMs | Sep 22, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/MarvellCareers/job/CA-ON---Toronto---TOR/Firmware-Engineer-Intern_2603751) |
| Marvell | Software/Firmware Engineer Intern | Hardware | CA-ON - Toronto - TOR | Python, C++, LLMs | Sep 22, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/MarvellCareers/job/CA-ON---Toronto---TOR/Software-Firmware-Engineer-Intern_2604053) |
| CIBC | Cloud Engineering Co-op | Software | Toronto, ON | Python, AWS, GCP, Azure | Sep 21, 2026 | [Apply](https://cibc.wd3.myworkdayjobs.com/campus/job/Toronto-ON/Cloud-Engineering-Co-op_2619386-1) |
| Autodesk | Product Management Intern, Stagiaire Gestion de Produit | PM | Montreal, QC, CAN | LLMs | Sep 19, 2026 | [Apply](https://autodesk.wd1.myworkdayjobs.com/uni/job/Montreal-QC-CAN/Product-Management-Intern--Stagiaire-Gestion-de-Produit_26WD101135-1) |
| Genesys | Software Developer, Intern (Genesys Cloud) | Software | Toronto (Flexible) | TypeScript, JavaScript, Vue, AWS | Sep 18, 2026 | [Apply](https://genesys.wd1.myworkdayjobs.com/Genesys/job/Toronto-Flexible/Software-Developer--Intern--Genesys-Cloud-_JR112244-1) |
| Genesys | Software Developer Full-Stack Intern, AI Scoring, Evaluations and Surveys | Data & ML/AI | Toronto (Flexible) | Python, Java, TypeScript, JavaScript | Sep 18, 2026 | [Apply](https://genesys.wd1.myworkdayjobs.com/Genesys/job/Toronto-Flexible/Software-Developer-Full-Stack-Intern--AI-Scoring--Evaluations-and-Surveys_JR112168-1) |
| Genesys | Software Developer Intern, Predictions Data & Decision Science | Data & ML/AI | Toronto (Flexible) | Python, Java, C++, C# | Sep 18, 2026 | [Apply](https://genesys.wd1.myworkdayjobs.com/Genesys/job/Toronto-Flexible/Software-Developer-Intern--Predictions-Data---Decision-Science_JR112176-1) |
| Keenfinity | Research Intern – AI-Based Audio Optimization | Data & ML/AI | Eindhoven +2 more | Python, C++, MATLAB | Sep 18, 2026 | [Apply](https://jobs.smartrecruiters.com/Keenfinity/744000150347490) |
| Rockwell Automation | Co-op, Robotics Research - Physical AI (OTTO at Rockwell Automation) 🛂 | Data & ML/AI | Waterloo, Ontario, Canada | PyTorch, ROS | Sep 17, 2026 | [Apply](https://rockwellautomation.wd1.myworkdayjobs.com/External_Rockwell_Automation/job/Waterloo-Ontario-Canada/Co-op--Robotics-Research---Physical-AI--OTTO-at-Rockwell-Automation-_R26-6872-1) |
| Rockwell Automation | Co-op, User Experience - Robotics (OTTO by Rockwell Automation) 🛂 | Design | Waterloo, Ontario, Canada | LLMs, React, ROS | Sep 17, 2026 | [Apply](https://rockwellautomation.wd1.myworkdayjobs.com/External_Rockwell_Automation/job/Waterloo-Ontario-Canada/Co-op--User-Experience---Robotics_R26-6732-1) |
| Autodesk | Intern, Software Developer/ Stagiaire en Développement Logiciel | Software | Montreal, QC, CAN | Java | Sep 17, 2026 | [Apply](https://autodesk.wd1.myworkdayjobs.com/uni/job/Montreal-QC-CAN/Intern--Software-Developer--Stagiaire-en-Dveloppement-Logiciel_26WD101114) |
| Ciena | AI & Automation Intern - GCN Services Business Operations | Data & ML/AI | Ottawa | No skills listed | Sep 16, 2026 | [Apply](https://ciena.wd5.myworkdayjobs.com/careers/job/Ottawa/AI---Automation-Intern---GCN-Services-Business-Operations_R031664) |
| Altera Corporation | Quartus Compiler Software - Intern | Software | Toronto, Ontario, Canada | C++, Verilog | Sep 15, 2026 | [Apply](https://altera.wd1.myworkdayjobs.com/altera/job/Toronto-Ontario-Canada/Quartus-Compiler-Software---Intern_R03108) |
| Nokia | Hardware Developer Eng Co-op/Intern | Hardware | Canada | No skills listed | Sep 15, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/39600) |
| Intelcom / Dragonfly | Back-end Developer Intern - Mobile Application | Software | Canada, Quebec, Montreal | Python, Java, C#, JavaScript | Sep 15, 2026 | [Apply](https://intelcomgroup.wd3.myworkdayjobs.com/Intelcom/job/Canada-Quebec-Montreal/Back-end-Developer-Intern---Mobile-Application_JR111747) |
| Cerebras | DevOps Engineer Intern - PEY | Software | Toronto, CAN | Python, Bash, AWS, Kubernetes | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/cerebras/c4faac59-3dbb-4ab7-9f74-d1fcbcddc7c6) |
| Eurofins | AI Compliance Internship | Data & ML/AI | Maastricht, LI, International (NL) | No skills listed | Sep 14, 2026 | [Apply](https://jobs.smartrecruiters.com/Eurofins/744000149363579) |
| Marvell | Firmware Engineer Intern | Hardware | Ottawa, Canada | Python, Bash, LLMs, Linux | Sep 14, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/marvellcareers2/job/Ottawa-Canada/Firmware-Engineer-Intern_2604738-1) |
| AstraZeneca | Data & Ai Solutions Intern | Data & ML/AI | Canada - Mississauga | Python, SQL, LLMs, AWS | Sep 11, 2026 | [Apply](https://astrazeneca.wd3.myworkdayjobs.com/Careers/job/Canada---Mississauga/Data---Ai-Solutions-Intern_R-259890) |
| Micron Technology | INTERNSHIP - NAND Cell Characterization & AI Tools | Data & ML/AI | Vimercate (MB), Italy | Python, C++, LLMs | Sep 11, 2026 | [Apply](https://micron.wd1.myworkdayjobs.com/External/job/Vimercate-MB-Italy/INTERNSHIP---NAND-Cell-Characterization---AI-Tools_JR111212) |
| AstraZeneca | AI Solutions & Automation Intern | Data & ML/AI | Canada - Mississauga | LLMs | Sep 10, 2026 | [Apply](https://astrazeneca.wd3.myworkdayjobs.com/Careers/job/Canada---Mississauga/AI-Solutions---Automation-Intern_R-259241) |
| Entrust | Intern - Software Developer - 8 months Hybrid in Ottawa | Software | Canada - Ottawa | React, Angular, Spring, AWS | Sep 07, 2026 | [Apply](https://entrust.wd1.myworkdayjobs.com/entrustcareers/job/Canada---Ottawa/Intern---Software-Developer---8-months-Hybrid-in-Ottawa_R004358) |
| Brave | Software Engineering Intern - Waterloo University | Software | Canada | Python, C++, Rust, TypeScript | Sep 04, 2026 | [Apply](https://job-boards.greenhouse.io/brave/jobs/8161945) |
| Teledyne | LiDAR Data Analyst (Co-op) | Data & ML/AI | Canada - Concord, ON (TDY) | Python, C++, MATLAB | Sep 03, 2026 | [Apply](https://flir.wd1.myworkdayjobs.com/flircareers/job/Canada---Concord-ON-TDY/LiDAR-Data-Analyst--Co-op-_REQ36378) |
| Intelcom / Dragonfly | Front-End Developer Intern - Power Platform Integration | Software | Canada, Quebec, Montreal | TypeScript, JavaScript, React, Azure | Sep 01, 2026 | [Apply](https://intelcomgroup.wd3.myworkdayjobs.com/Intelcom/job/Canada-Quebec-Montreal/Front-End-Developer-Intern---Power-Platform-Integration_JR111615-1) |
| Intelcom / Dragonfly | Software Development Intern - Address Intelligence Platform | Software | Canada, Quebec, Montreal | Python, Java, C#, TypeScript | Sep 01, 2026 | [Apply](https://intelcomgroup.wd3.myworkdayjobs.com/Intelcom/job/Canada-Quebec-Montreal/Software-Development-Intern---Address-Intelligence-Platform_JR111611) |
| Stripe | Software Engineer, Intern (Summer or Winter) | Software | Toronto | Java, JavaScript, Scala, Ruby | Aug 31, 2026 | [Apply](https://stripe.com/jobs/search?gh_jid=8130805) |

<a id="japan"></a>
## Recently posted — cycle not stated — Japan  (1 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Bosch | 【MA】Internship Regional Product Manager in Aftermarket Asia Pacific South | PM | Bosch Corporation_Internship +2 more | Python, SQL | Sep 18, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000150296334) |

<a id="iec"></a>
## Summer 2027 — IEC countries  (55 employer-stated)

Located in Australia, Austria, Chile, Costa Rica, Croatia, Czech Republic, Estonia, France, Germany, Greece, Ireland, Italy, Latvia, Lithuania, Luxembourg, Norway, Poland, Portugal, Slovakia, Slovenia, Spain, Sweden, Switzerland, Taiwan, and United Kingdom.

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Hewlett Packard Enterprise | Software Engineering Internship (Placement Year) 🆕 | Software | Bristol, Avon, United Kingdom | Python, Java, C++, C# | Sep 23, 2026 | [Apply](https://hpe.wd5.myworkdayjobs.com/Jobsathpe/job/Bristol-Avon-United-Kingdom/Software-Engineering-Internship--Placement-Year-_1215804) |
| Hudson River Trading | Data Scientist Intern - 2027 | Data & ML/AI | London, United Kingdom | Python, Pandas | Sep 22, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8222413) |
| Snowflake | Software Engineer Intern - Berlin (2027) | Software | DE-Berlin-Trion Building | Java, C++, SQL, AWS | Sep 22, 2026 | [Apply](https://jobs.ashbyhq.com/snowflake/ab028e3c-c1cf-4455-8915-8e4e6b0cc9e8) |
| DV Trading | Security Engineer Intern - Summer 2027 | Security | London | Python, Linux | Sep 22, 2026 | [Apply](https://job-boards.greenhouse.io/dvtrading/jobs/4736603005) |
| Amazon | 2027 Software Dev Engineer Intern - Spain | Software | Madrid, International | Python, Java, C++, C# | Sep 22, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10555855/2027-software-dev-engineer-intern-spain) |
| Amazon | 2027 Software Dev Engineer Intern - Italy | Software | Turin, International | Python, Java, C++, C# | Sep 22, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10555867/2027-software-dev-engineer-intern-italy) |
| Amazon | 2027 Software Dev Engineer Intern - Poland | Software | Gdansk, International | Python, Java, C++, C# | Sep 22, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10555873/2027-software-dev-engineer-intern-poland) |
| JPMorganChase | 2027 Quantitative Research – Asset Management - Summer Analyst Internship - London | Quant | LONDON, LONDON, United Kingdom | Python, Java, C++, SQL | Sep 22, 2026 | [Apply](https://jpmc.fa.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/210792010) |
| Brevan Howard | 2027 Summer Internship Program - AI & Quantitative Analyst, London | Quant | London | Python, LLMs | Sep 22, 2026 | [Apply](https://wd3.myworkdaysite.com/recruiting/brevanhoward/BH_ExternalCareers/job/London/AI---Quantitative-Analyst--London_JR101605) |
| American Express | Campus - Internship Programme - Undergraduate GMNS Digital Product Management - 2027 (UK) | PM | LONDON, United Kingdom | No skills listed | Sep 21, 2026 | [Apply](https://egug.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26014306) |
| WTW | 2027 Data Scientist Internship Programme - P&C Insurance - London/Reigate | Data & ML/AI | London +5 more | Python, SQL, LLMs | Sep 18, 2026 | [Apply](https://eedu.fa.em3.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1003/job/202605997) |
| Schroders | 2027 Product Internship Programme | Other | London, United Kingdom | No skills listed | Sep 18, 2026 | [Apply](https://ekbq.fa.em2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2/job/1952) |
| Cogna | Software Engineer Intern (2027 Cohort) | Software | London, England, United Kingdom (Hybrid) | Python, Java, C++, C# | Sep 18, 2026 | [Apply](https://apply.workable.com/cogna/j/45A6283F88/) |
| Rothesay | 2027 Summer Internship Programme - Quantitative Strategist | Quant | London | Python, C++ | Sep 17, 2026 | [Apply](https://job-boards.greenhouse.io/rothesaygraduates/jobs/8811533002) |
| Talos | Software Engineer Intern, Trading | Quant | London | Java, C++, Git, PostgreSQL | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/talos-trading/42cad756-c312-4142-a9b7-18ed76f61c5d) |
| Talos | Software Engineer Intern, Infrastructure | Software | London | Python, Java, Bash, AWS | Sep 16, 2026 | [Apply](https://jobs.ashbyhq.com/talos-trading/f2a0aaa2-af88-4715-9f2d-8f61bd5e2935) |
| Schonfeld | 2027 DMFI Quant Developer Intern | Quant | London, England, United Kingdom | Python, C++ | Sep 16, 2026 | [Apply](https://job-boards.greenhouse.io/schonfeld/jobs/8207942) |
| Figma | Software Engineer Intern (London, United Kingdom) (Summer 2027) | Software | London, England | Python, Java, C++, JavaScript | Sep 14, 2026 | [Apply](https://boards.greenhouse.io/figma/jobs/6152695004?gh_jid=6152695004) |
| Scale AI | Software Engineering Intern (Summer 2027) | Software | London, UK | Python, TypeScript, LLMs, React | Sep 14, 2026 | [Apply](https://job-boards.greenhouse.io/scaleai/jobs/4730846005) |
| American Express | Campus - Internship Programme - Undergraduate - AI Engineer - 2027 (UK - Burgess Hill) | Data & ML/AI | BURGESS HILL +2 more | Python, Java, JavaScript, SQL | Sep 14, 2026 | [Apply](https://egug.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26013756) |
| American Express | Campus - Internship Programme - Undergraduate - AI Engineer - 2027 (UK - London) | Data & ML/AI | LONDON, United Kingdom | Python, Java, JavaScript, SQL | Sep 14, 2026 | [Apply](https://egug.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/26013758) |
| Garrett Motion | International Internship Czech Republic 2027- AI in Embedded SW development | Data & ML/AI | BRNO MĚSTO, Czech Republic | Python, MATLAB | Sep 11, 2026 | [Apply](https://ehth.fa.em2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_2001/job/15037) |
| TTP | Summer Internship - Software Engineering Consultant - 2027 | Software | Melbourn, England, United Kingdom | No skills listed | Sep 11, 2026 | [Apply](https://jobs.smartrecruiters.com/TTP1/744000149038758) |
| Sentry | Software Engineer, Intern (Summer 2027) | Software | Vienna, Austria | Python, JavaScript, AWS, Git | Sep 10, 2026 | [Apply](https://jobs.ashbyhq.com/sentry/fa522ac5-fc9f-4ce1-a191-842496a235a2) |
| Datadog | Software Engineering Intern | Software | Paris, France | Kubernetes | Sep 08, 2026 | [Apply](https://careers.datadoghq.com/detail/8114186/?gh_jid=8114186) |
| Datadog | Product Management Intern | PM | Paris, France | No skills listed | Sep 08, 2026 | [Apply](https://careers.datadoghq.com/detail/8143729/?gh_jid=8143729) |
| Schonfeld | 2027 DMFI Quant Research Intern | Quant | London, England, United Kingdom | Python, C++, C#, Rust | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/schonfeld/jobs/8187178) |
| BNY | 2027 BNY Summer Internship Program - Product Management (London) | PM | London, United Kingdom | No skills listed | Sep 08, 2026 | [Apply](https://eofe.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/81922) |
| JPMorganChase | 2027 Quantitative Research Markets Analyst Program – Off-Cycle Internship – London | Quant | LONDON, LONDON, United Kingdom | Python, C++ | Sep 07, 2026 | [Apply](https://jpmc.fa.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/210788659) |
| Marshall Wace | Quant Research Intern - London - 2027 | Quant | London | Python, MATLAB | Sep 02, 2026 | [Apply](https://job-boards.greenhouse.io/mwinternshipprogram/jobs/8772688002) |
| Maven Securities | Software Developer Summer Internship London 2027 | Software | London | Python, C++, C#, TypeScript | Sep 01, 2026 | [Apply](https://job-boards.greenhouse.io/mavensecuritiesholdingltd/jobs/7806987) |
| Tower Research Capital | Quantitative Trader/Researcher Summer Internship 2027 (2028 Graduates) | Quant | London | Python, C++ | Sep 01, 2026 | [Apply](https://www.tower-research.com/open-positions/?gh_jid=8037860) |
| NVIDIA | Developer Technology Engineering Intern, HPC and AI - 2027 | Data & ML/AI | Taiwan, Taipei | C++, CUDA | Sep 01, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/Taiwan-Taipei/Developer-Technology-Engineering-Intern--HPC-and-AI---2027_JR2024509) |
| PIMCO | 2027 Summer Intern - Client Solutions & Analytics Quantitative Research Analyst (MFE), London | Quant | London, GBR | Python, MATLAB | Sep 01, 2026 | [Apply](https://pimco.wd1.myworkdayjobs.com/pimco-careers/job/London-GBR/XMLNAME-2027-Summer-Intern---Client-Solutions---Analytics-Strategist--London--MBA-_R106804) |
| JPMorganChase | 2027 Software Engineer Program - Summer Internship - Glasgow, London | Software | LONDON +5 more | No skills listed | Aug 31, 2026 | [Apply](https://jpmc.fa.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/210774716) |
| FTI Consulting | 2027 Intern, Forensic & Litigation Consulting, Cyber | Security | Paris, France | No skills listed | Aug 31, 2026 | [Apply](https://fticonsulting.wd108.myworkdayjobs.com/FTIConsultingCareers/job/Paris-France/XMLNAME-2027-Intern--Forensic---Litigation-Consulting--Cyber_JR260757) |
| PIMCO | 2027 Summer Intern – Product Analyst, EMEA | PM | London, GBR | No skills listed | Aug 31, 2026 | [Apply](https://pimco.wd1.myworkdayjobs.com/pimco-careers/job/London-GBR/XMLNAME-2027-Summer-Intern---Product-Analyst--EMEA_R106780) |
| PIMCO | 2027 Summer Intern - Technology Analyst, Software Engineering, EMEA | Software | London, GBR | Python, Java, C++, C# | Aug 31, 2026 | [Apply](https://pimco.wd1.myworkdayjobs.com/pimco-careers/job/London-GBR/XMLNAME-2027-Summer-Intern---Technology-Analyst--Software-Engineering--EMEA_R106800) |
| TELUS Digital | Data & AI Intern (Brazil) - Year Round 2027 | Data & ML/AI | Porto Alegre, Brazil | Python, SQL, LLMs | Aug 28, 2026 | [Apply](https://jobs.ashbyhq.com/telus-digital/89730055-fa03-444d-aa05-0058946fa436) |
| TELUS Digital | Software Engineering Intern (Brazil) - Year Round 2027 | Software | Porto Alegre, Brazil | No skills listed | Aug 28, 2026 | [Apply](https://jobs.ashbyhq.com/telus-digital/98495440-1a32-4c7e-8183-f38beebfd1d0) |
| BNY | 2027 BNY Internship Program -Engineering (Developer) (Manchester) | Software | Greater Manchester, United Kingdom | Python, Java, JavaScript, HTML/CSS | Aug 24, 2026 | [Apply](https://eofe.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/81318) |
| BNY | 2027 BNY Internship Program -Engineering (Data Science) (Manchester) | Data & ML/AI | Greater Manchester, United Kingdom | Python, Java, JavaScript, HTML/CSS | Aug 24, 2026 | [Apply](https://eofe.fa.us2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1001/job/81322) |
| NVIDIA | System Software Engineer – GPU and SOC (2027 RDSS Intern) | Software | Taiwan, Taipei | C++, Linux | Aug 19, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/Taiwan-Taipei/System-Software-Engineer---GPU-and-SOC--2027-RDSS-Intern-_JR2023628) |
| Xantium | Quantitative Developer Intern | Quant | London, England, New York, New York | Python, C++ | Aug 17, 2026 | [Apply](https://job-boards.greenhouse.io/xantium/jobs/4360768009) |
| Xantium | Quantitative Researcher Intern | Quant | London, England, New York, New York | No skills listed | Aug 17, 2026 | [Apply](https://job-boards.greenhouse.io/xantium/jobs/4371217009) |
| DV Trading | Software Engineer Intern - Summer 2027 (DV Commodities) | Software | London | Python, C++ | Aug 10, 2026 | [Apply](https://job-boards.greenhouse.io/dvtrading/jobs/4719125005) |
| Autodesk | Software Engineering Intern Summer 2027 🆕 | Software | Norway - Oslo | No skills listed | Aug 05, 2026 | [Apply](https://autodesk.wd1.myworkdayjobs.com/uni/job/Norway---Oslo/Software-Engineering-Intern-Summer-2027_26WD100046-3) |
| Maven Securities | Quant Trader Internship 2027 (6 months) | Quant | London | Python, C++, C# | Jul 31, 2026 | [Apply](https://job-boards.greenhouse.io/mavensecuritiesholdingltd/jobs/8043552) |
| Chicago Trading Company | Quant Trading Internship - Summer 2027 | Quant | London, England, United Kingdom | Python | Jul 21, 2026 | [Apply](https://job-boards.greenhouse.io/ctccampusboard/jobs/4709545005) |
| Virtu Financial | 2027 Internship - Software Engineer | Software | Dublin, Ireland | No skills listed | Jul 20, 2026 | [Apply](https://job-boards.greenhouse.io/virtu/jobs/8551566002) |
| Hudson River Trading | Algorithm Development (Quant Research & Trading) Internship – Summer 2027 | Quant | London +5 more | Python, C++, MATLAB, Pandas | Jul 13, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=7964062) |
| Hudson River Trading | Software Engineering Internship (C++ or Python) – Summer 2027 | Software | Austin +11 more | Python, C++ | Jul 13, 2026 | [Apply](https://www.hudsonrivertrading.com/careers/job/?gh_jid=8052083) |
| Virtu Financial | 2027 Internship - Quantitative Trading | Quant | Dublin, Ireland | Python, Java, C++, SQL | Jul 01, 2026 | [Apply](https://job-boards.greenhouse.io/virtu/jobs/8547254002) |
| IMC Trading | Machine Learning Research Intern - Summer 2027 - Sydney | Data & ML/AI | Sydney,  Australia | Python, PyTorch, TensorFlow | Jul 01, 2026 | [Apply](https://job-boards.eu.greenhouse.io/imc/jobs/4956547101) |
| Aquatic Capital Management | Quantitative Researcher, Intern (Summer 2027) | Quant | Chicago; London | Python | Apr 01, 2026 | [Apply](https://job-boards.greenhouse.io/aquaticcapitalmanagement/jobs/8489186002) |

## Recently posted — cycle not stated — IEC countries  (91 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Motorola | Software Engineering Internship 🆕 | Software | Cork, Ireland | C++, Linux, Git | Sep 24, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Cork-Ireland/Software-Engineering-Internship_R66949-1) |
| Bertelsmann | Internship in Information Security Services 🆕 | Security | Luxembourg, International (LU) | No skills listed | Sep 24, 2026 | [Apply](https://jobs.smartrecruiters.com/Bertelsmann-Jobs/744000151659959) |
| Bosch | Extracurricular Internship in Computer Science / Information Systems (f/m/div.) 🆕 | Software | Braga, International (PT) | JavaScript, SQL, React, Vue | Sep 24, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000151644699) |
| Ferrovial | AI Program Internship 🆕 | Data & ML/AI | Madrid | LLMs, Azure | Sep 24, 2026 | [Apply](https://ferrovial.wd3.myworkdayjobs.com/ferrovial_career_site/job/Madrid/AI-Program-Internship_JR19467) |
| Johnson & Johnson | Data Science & Process Modeling Intern 🆕 | Data & ML/AI | Schaffhausen, Switzerland | Python, MATLAB | Sep 24, 2026 | [Apply](https://jj.wd5.myworkdayjobs.com/JJ/job/Schaffhausen-Switzerland/Data-Science---Process-Modeling-Intern_R-101009) |
| Logitech | C++ Software Developer Intern (3-month contract) 🆕 | Software | Krakow, Poland | C++, Bash, Linux | Sep 24, 2026 | [Apply](https://logitech.wd5.myworkdayjobs.com/Logitech/job/Krakow-Poland/C---Software-Developer-Intern--3-month-contract-_148315) |
| Logitech | Software Engineer Intern (3-month contract) 🆕 | Software | Krakow, Poland | Java, C++, Kotlin, Bash | Sep 24, 2026 | [Apply](https://logitech.wd5.myworkdayjobs.com/Logitech/job/Krakow-Poland/Software-Engineer-Intern--3-month-contract-_148290) |
| Logitech | Software QA Intern, Engineering (3-month contract) 🆕 | Software | Krakow, Poland | Python, Bash, Linux | Sep 24, 2026 | [Apply](https://logitech.wd5.myworkdayjobs.com/Logitech/job/Krakow-Poland/Software-QA-Intern--Engineering--3-month-contract-_148297-1) |
| PricewaterhouseCoopers (PwC) | Data Engineer Intern 🆕 | Data & ML/AI | Prague | Python, LLMs, AWS, GCP | Sep 24, 2026 | [Apply](https://pwc.wd3.myworkdayjobs.com/Global_Campus_Careers/job/Prague/Datov-internship-v-Technology-Consultingu_742242WD-1) |
| ABB | Student Internship - UX Designer 🆕 | Design | Lodz, Lodz, Poland | No skills listed | Sep 24, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Lodz-Lodz-Poland/Student-Internship---UX-Designer_JR00048119-1) |
| NXP Semiconductors | Intern (f/m/d) AI-Driven Data Analysis for Non-Volatile Memory Design 🆕 | Data & ML/AI | Hamburg | Linux, Verilog | Sep 24, 2026 | [Apply](https://nxp.wd3.myworkdayjobs.com/careers/job/Hamburg/Intern--f-m-d--AI-Driven-Data-Analysis-for-Non-Volatile-Memory-Design_R-10066893) |
| Coram AI | Software Engineer - Internship 🆕 | Software | London | Python, Go, TypeScript, LLMs | Sep 23, 2026 | [Apply](https://jobs.ashbyhq.com/coram-ai/0c4bb1e4-0d05-40b5-a61c-6db475e21640) |
| ABB | Student Internship - UX Designer 🆕 | Design | Krakow, Lesser Poland, Poland | No skills listed | Sep 23, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Krakow-Lesser-Poland-Poland/Student-Internship---UX-Designer_JR00048119-1) |
| Wavestone | Internship Wavestone Luxembourg - Cybersecurity & Artificial Intelligence Consulting 🆕 | Data & ML/AI | Leideleng +2 more | Python, LLMs | Sep 23, 2026 | [Apply](https://jobs.smartrecruiters.com/Wavestone1/744000151373865) |
| Flextronics International | Software Quality Engineer- Internship 🆕 | Software | Italy, Milano | No skills listed | Sep 23, 2026 | [Apply](https://flextronics.wd1.myworkdayjobs.com/Careers/job/Italy-Milano/Software-Quality-Engineer_WD230181) |
| Johnson Controls | Architecture & AI Intern 🆕 | Data & ML/AI | Cork-County Cork-Ireland | LLMs, AWS, Azure | Sep 23, 2026 | [Apply](https://jci.wd5.myworkdayjobs.com/JCI/job/Cork-County-Cork-Ireland/Architecture---AI-Intern_WD30279250) |
| Marvell | Software Engineer Intern 🆕 | Software | Madrid | Python, C++ | Sep 23, 2026 | [Apply](https://marvell.wd1.myworkdayjobs.com/MarvellCareers/job/Madrid/Software-Engineer-Intern_2604258) |
| Motorola | Intern Software Developer (React/JS) 🆕 | Software | Krakow, Poland | React, Python, JavaScript, Node.js | Sep 23, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Krakow-Poland/Intern-Software-Developer--React-JS-_R68879) |
| Procter & Gamble (P&G) | Analysis & Insights Internship (Stagiaire Data Analyst) 🆕 | Data & ML/AI | PARIS GO-ASNIERES-SUR-SEINE | Python, SQL | Sep 22, 2026 | [Apply](https://pg.wd5.myworkdayjobs.com/1000/job/PARIS-GO-ASNIERES-SUR-SEINE/Analysis---Insights-Internship--Stagiaire-Data-Analyst-_R000159355) |
| Airbus | Internship (d/f/m) within Airbus site Artificial Intelligence Centre (AIC) | Data & ML/AI | Bremen Area | Python, PyTorch, TensorFlow | Sep 22, 2026 | [Apply](https://ag.wd3.myworkdayjobs.com/Airbus/job/Bremen-Area/Internship--d-f-m--within-Airbus-site-Artificial-Intelligence-Centre--AIC-_JR10441522) |
| Procter & Gamble (P&G) | Analysis & Insights Internship (Stagiaire Data Analyst) | Data & ML/AI | PARIS GO: SAINT-OUEN GO | Python, SQL | Sep 22, 2026 | [Apply](https://pg.wd5.myworkdayjobs.com/1000/job/PARIS-GO-SAINT-OUEN-GO/Analysis---Insights-Internship--Stagiaire-Data-Analyst-_R000159355) |
| SOTI | Software Development & QA Intern Opportunities 26/27 | Software | Galway, Ireland | C#, JavaScript, SQL, Node.js | Sep 22, 2026 | [Apply](https://soti.wd3.myworkdayjobs.com/Careers/job/Galway-Ireland/Software-Development---QA-Intern-Opportunities-26-27_R10547) |
| Leidos | Intern Software Developer | Software | Melbourne, Victoria, Australia | No skills listed | Sep 22, 2026 | [Apply](https://leidos.wd5.myworkdayjobs.com/External/job/Melbourne-Victoria-Australia/Intern-Software-Developer_R-00190834) |
| NVIDIA | System Software Engineer - USB (RDSS Intern) | Software | Taiwan, Taipei | C++, Linux | Sep 22, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/Taiwan-Taipei/System-Software-Engineer---USB--RDSS-Intern-_JR2025914-1) |
| Wex | Software Engineering Intern | Software | Melbourne, Australia | Python, Java, C#, TypeScript | Sep 22, 2026 | [Apply](https://wexinc.wd5.myworkdayjobs.com/WEXInc/job/Melbourne-Australia/Software-Development-Intern_R22903) |
| Chanel | Information Security Intern – Governance, Risk & Compliance (GRC) | Security | London | No skills listed | Sep 21, 2026 | [Apply](https://cc.wd3.myworkdayjobs.com/ChanelCareers/job/London/Information-Security-Intern---Governance--Risk---Compliance--GRC-_JOBREQ00115341) |
| G-Research | Software Engineering Internship | Software | London, UK | Java, C++, C# | Sep 21, 2026 | [Apply](https://gresearch.wd103.myworkdayjobs.com/G-Research/job/London-UK/Software-Engineering-Intern_R3746) |
| CWAN | Product Management Intern | PM | Office - London | Python, SQL | Sep 18, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---London/Product-Management-Intern_R12199) |
| Ferrovial | AI Engineer Internship | Data & ML/AI | Madrid | Python, PyTorch, TensorFlow, scikit-learn | Sep 18, 2026 | [Apply](https://ferrovial.wd3.myworkdayjobs.com/ferrovial_career_site/job/Madrid/AI-Engineer-Internship_JR19380) |
| Sun Life | Jr. Analytics and Automation Developer Intern | Data & ML/AI | Waterford, Waterford, Ireland | Python, Java, C++ | Sep 18, 2026 | [Apply](https://sunlife.wd3.myworkdayjobs.com/Experienced-Jobs/job/Waterford-Waterford-Ireland/Jr-Analytics-and-Automation-Developer-Intern_JR00128023) |
| Bosch | DATA ANALYST INTERN | Data & ML/AI | San Francisco +2 more | Python, SQL, Pandas, Git | Sep 17, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000150216697) |
| Bosch | WEB DEVELOPER INTERN (PYTHON & AUTOMATION) | Software | San Francisco +2 more | Python, JavaScript, Angular, HTML/CSS | Sep 16, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000149963299) |
| Javelin Global Commodities | Summer Intern: Software Engineering | Software | London, England, United Kingdom | No skills listed | Sep 16, 2026 | [Apply](https://apply.workable.com/javelin-global-commodities/j/C2B7BC10AD/) |
| F5 | Software Engineering Intern | Software | Cork | Python, Kubernetes | Sep 16, 2026 | [Apply](https://ffive.wd5.myworkdayjobs.com/f5jobs/job/Cork/Software-Engineering-Intern_RP1038785) |
| NVIDIA | Software Engineering Intern — Replay Tooling and Test Automation - Autonomous Driving | Software | Germany, Munich | Python, C++, Linux, Git | Sep 16, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/Germany-Munich/Software-Engineering-Intern---Replay-Tooling---Test-Automation--Autonomous-Driving_JR2022086) |
| NVIDIA | Firmware Application Engineer (RDSS Intern) | Hardware | Taiwan, Taipei | Python, C++, Linux | Sep 16, 2026 | [Apply](https://nvidia.wd5.myworkdayjobs.com/NVIDIAExternalCareerSite/job/Taiwan-Taipei/Firmware-Application-Engineer--RDSS-Intern-_JR2024884) |
| PricewaterhouseCoopers (PwC) | Cloud Infrastructure Intern - Milano 🇨🇦 | Software | Milan | No skills listed | Sep 16, 2026 | [Apply](https://pwc.wd3.myworkdayjobs.com/Global_Campus_Careers/job/Milan/Cloud-Infrastructure-Intern---Milano_741403WD-1) |
| Sia Partners | Final year Internship - CIO, Data & AI Advisory 🆕 _(2 openings)_ | Data & ML/AI | Paris, IDF, International (FR) | No skills listed | Sep 15, 2026 | [Apply](https://jobs.smartrecruiters.com/Sia/744000149618239) [#2](https://jobs.smartrecruiters.com/Sia/744000151389740) |
| CWAN | Software Development Intern _(2 openings)_ | Software | Office - London | Java | Sep 15, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---London/Software-Development-Intern_R12096) [#2](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---London/Software-Development-Intern_R12097) |
| CWAN | Technical Product Management Intern | PM | Office - London | Java | Sep 15, 2026 | [Apply](https://clearwateranalytics.wd1.myworkdayjobs.com/Clearwater_Analytics_Careers/job/Office---London/Technical-Product-Management-Intern_R12197) |
| Kyndryl | Devops Intern | Software | Athens, Attiki, Greece | No skills listed | Sep 15, 2026 | [Apply](https://kyndryl.wd5.myworkdayjobs.com/KyndrylProfessionalCareers/job/Athens-Attiki-Greece/Devops-Intern_R-65079-1) |
| Kyndryl | Middleware Software Intern | Software | Athens, Attiki, Greece | No skills listed | Sep 15, 2026 | [Apply](https://kyndryl.wd5.myworkdayjobs.com/KyndrylProfessionalCareers/job/Athens-Attiki-Greece/Middleware-Software-Intern_R-65081-1) |
| SPAICE Technology | Software Engineering Intern | Software | London | Python, C++, Linux, Git | Sep 14, 2026 | [Apply](https://jobs.ashbyhq.com/spaice-tech/16468d27-11e9-498c-87b6-3469f5f4ee12) |
| Citco | AI Intern - 6 Months (2 positions) | Data & ML/AI | Dublin, Co. Dublin, Ireland | Python, LLMs, AWS, Git | Sep 14, 2026 | [Apply](https://fa-euxc-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/16490) |
| Sia Partners | Final year internship - Data Scientist & AI Consultant | Data & ML/AI | Paris, IDF, International (FR) | Python, PyTorch, TensorFlow, LLMs | Sep 14, 2026 | [Apply](https://jobs.smartrecruiters.com/Sia/744000149281258) |
| Chanel | Internship - Cyber Transformation Officer GISEC | Security | London | No skills listed | Sep 14, 2026 | [Apply](https://cc.wd3.myworkdayjobs.com/ChanelCareers/job/London/Internship---Cyber-Transformation-Officer-GISEC_JOBREQ00115118) |
| Deutsche Bank | Internship Innovation and AI - Cards Issuing and Acquiring - Milano (f/m/x) | Data & ML/AI | Milano Bicocca Calendario 3 | No skills listed | Sep 14, 2026 | [Apply](https://db.wd3.myworkdayjobs.com/DBWebsite/job/Milano-Bicocca-Calendario-3/Internship-Innovation-and-AI---Cards-Issuing-and-Acquiring---Milano--f-m-x-_R0449341) |
| Census | Internship: IT Systems & AI Ops | Data & ML/AI | Athens, GR | No skills listed | Sep 11, 2026 | [Apply](https://census.breezy.hr/p/f8f39bc1b11f01-internship-it-systems-ai-ops) |
| Nokia | AI Software Engineer – Intern | Data & ML/AI | Italy | Python, Java, C#, SQL | Sep 11, 2026 | [Apply](https://fa-evmr-saasfaprod1.fa.ocs.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/40280) |
| American Tower | Internship - AI Project Coordinator (6 months) | Data & ML/AI | Bagneux, France | No skills listed | Sep 11, 2026 | [Apply](https://hdsn.fa.us6.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/2948) |
| Arista Networks 🆁 | Intern Software Engineer - C/C++ | Software | Poland - Remote +1 more | C++, Python, Linux, Git | Sep 11, 2026 | [Apply](https://jobs.smartrecruiters.com/AristaNetworks/744000149101159) |
| Sia Partners | Final year internship - DevOps / Platform Engineer | Software | Paris, IDF, International (FR) | Python, AWS, GCP, Azure | Sep 11, 2026 | [Apply](https://jobs.smartrecruiters.com/Sia/744000148977039) |
| Fifty-Five | Data Science Consultant Intern (H/F) | Data & ML/AI | Paris, Île-de-France, France | SQL, Tableau | Sep 11, 2026 | [Apply](https://apply.workable.com/fifty-five/j/D8F4443694/) |
| Celonis | Intern Deployment Engineer - Data & AI | Data & ML/AI | Munich, Germany | Python, SQL | Sep 10, 2026 | [Apply](https://job-boards.greenhouse.io/celonis/jobs/7990983003?gh_jid=7990983003) |
| Red Bull | Internship Data Science | Data & ML/AI | Elsbethen, Salzburg, International (AT) | Python, SQL, Snowflake | Sep 10, 2026 | [Apply](https://jobs.smartrecruiters.com/RedBull/744000148756269) |
| Motorola | Intern Software Developer (C#) | Software | Krakow, Poland | C#, SQL, .NET, Azure | Sep 10, 2026 | [Apply](https://motorolasolutions.wd5.myworkdayjobs.com/Careers/job/Krakow-Poland/Intern-Software-Developer--C--_R67818) |
| PHINIA | HRIS Intern – Workday & AI Agent Deployment | Data & ML/AI | Cinisello - Italy | No skills listed | Sep 10, 2026 | [Apply](https://phinia.wd5.myworkdayjobs.com/PHINIA_Careers/job/Cinisello---Italy/HRIS-Intern---Workday---AI-Agent-Deployment_R2026-0579) |
| Tencent | Cyber Security Intern | Security | United Kingdom-London | Python, AWS, GCP, Azure | Sep 10, 2026 | [Apply](https://tencent.wd1.myworkdayjobs.com/Tencent_Careers/job/United-Kingdom-London/Cyber-Security-Intern_R108126) |
| Zeiss | Internship – Physical AI for Surgical Robotics (f/m/x) | Data & ML/AI | Karlsruhe | Python, PyTorch, Computer Vision | Sep 10, 2026 | [Apply](https://zeissgroup.wd3.myworkdayjobs.com/External/job/Karlsruhe/Internship---Physical-AI-for-Surgical-Robotics--f-m-x-_JR_1052834) |
| Celonis | AI & Management Consulting Intern (Value Engineering - UKI Market) | Data & ML/AI | London, United Kingdom | Python, SQL, LLMs | Sep 09, 2026 | [Apply](https://job-boards.greenhouse.io/celonis/jobs/7986192003?gh_jid=7986192003) |
| Toast | Software Engineering Intern | Software | Dublin, Ireland | Python, Java, JavaScript, SQL | Sep 09, 2026 | [Apply](https://careers.toasttab.com/jobs?gh_jid=8187654) |
| Fasanara | Quant Trading Intern | Quant | London, England, United Kingdom | Python, SQL | Sep 09, 2026 | [Apply](https://apply.workable.com/fasanara/j/FC82BCC5C5/) |
| Ecolab | Intern Data Science - Alumnos/as Regulares de último/s año/s de carrera | Data & ML/AI | CHL - Region Metropolitana de Santiago… | No skills listed | Sep 09, 2026 | [Apply](https://ecolab.wd1.myworkdayjobs.com/ecolab_external/job/CHL---Region-Metropolitana-de-Santiago---Santiago/Intern-Data-Science---Alumnos-as-Regulares-de-ltimo-s-ao-s-de-carrera_R00301332) |
| Zeiss | Internship – AI for Neural Signal Processing in Healthcare Innovation (f/m/x) | Data & ML/AI | Karlsruhe | Python, C++, PyTorch, Azure | Sep 09, 2026 | [Apply](https://zeissgroup.wd3.myworkdayjobs.com/External/job/Karlsruhe/Internship---AI-for-Neural-Signal-Processing-in-Healthcare-Innovation--f-m-x-_JR_1052727-1) |
| Artefact | Data Scientist Intern - Paris | Data & ML/AI | 9th arrondissement of Paris +3 more | AWS, GCP, Azure | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/artefactlinkedin/jobs/8785636002) |
| Snowflake | Applied AI Intern - Warsaw | Data & ML/AI | PL-Warsaw-Lixa C | Python, SQL, LLMs, AWS | Sep 08, 2026 | [Apply](https://jobs.ashbyhq.com/snowflake/90190b16-fd27-4366-8c10-9c4896157681) |
| WPP Media | Intern AI, Data & Tech | Data & ML/AI | Oslo, Norway | SQL, GCP | Sep 08, 2026 | [Apply](https://job-boards.greenhouse.io/wppmedia/jobs/5413592008) |
| Auctane | CyberSecurity - Interns | Security | Wrocław, PL | Python, Bash, Linux | Sep 07, 2026 | [Apply](https://job-boards.greenhouse.io/auctane/jobs/7977819003) |
| Arcadis | Summer Intern - Process Engineer APM | PM | Dublin +6 more | No skills listed | Sep 07, 2026 | [Apply](https://ebcs.fa.em2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/43788) |
| Arcadis | Summer Intern - Instrumentation Engineer APM | PM | Cork, Munster, Ireland | No skills listed | Sep 07, 2026 | [Apply](https://ebcs.fa.em2.oraclecloud.com/hcmUI/CandidateExperience/en/sites/CX_1/job/43791) |
| Kobo | Software Developer Intern (Dublin) | Software | Dublin, Ireland | Java, C#, JavaScript, SQL | Sep 07, 2026 | [Apply](https://rakuten.wd1.myworkdayjobs.com/Kobo/job/Dublin-Ireland/Software-Developer-Intern--Dublin-_1037090-1) |
| Sereact | Product Manager Intern (m/f/d) | PM | Stuttgart Schockenriedstr. 17 | ROS | Sep 04, 2026 | [Apply](https://jobs.ashbyhq.com/sereact/7549093b-0918-4136-ac47-81063ded166d) |
| Euronext | Quant Intern | Quant | Paris | Python, MATLAB, Tableau | Sep 04, 2026 | [Apply](https://hrhub.wd3.myworkdayjobs.com/Euronext_Career_Page/job/Paris/Quant-Intern_R28576) |
| JINGDONG | JD Young Product Management Internship | PM | GBR-London | SQL, Tableau | Sep 03, 2026 | [Apply](https://jd.wd103.myworkdayjobs.com/Campus_Career_Site/job/GBR-London/JD-Young-Product-Management-Internship_JR103809) |
| Thales | DevOps Intern | Software | Madrid | Python, Angular, Azure | Sep 03, 2026 | [Apply](https://thales.wd3.myworkdayjobs.com/careers/job/Madrid/DevOps-Intern_R0336368-1) |
| Perplexity AI | Internship - Machine Learning Research Engineer | Data & ML/AI | Berlin | PyTorch | Sep 02, 2026 | [Apply](https://jobs.ashbyhq.com/perplexity/b9e1ff15-d52a-46d5-abf0-26460f2a116c) |
| ABB | Internship - OT Cybersecurity | Security | Genova, Genova, Italy | Linux | Sep 02, 2026 | [Apply](https://abb.wd3.myworkdayjobs.com/external_career_page/job/Genova-Genova-Italy/Internship---Cybersecurity-for-OT-Systems_JR00042894) |
| Hitachi Energy 🆁 | Internship - Software Asset Management | Software | Remote - Lesser Poland, Poland | No skills listed | Sep 02, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Remote---Lesser-Poland-Poland/Internship---Software-Asset-Management_R0139768-1) |
| Thales | Software Engineering Intern | Software | Madrid | Java, C#, TypeScript, JavaScript | Sep 02, 2026 | [Apply](https://thales.wd3.myworkdayjobs.com/careers/job/Madrid/Software-Engineering-Intern_R0336381-1) |
| Tower Research Capital | Quantitative Researcher Intern, Bachelor's or Master's | Quant | Singapore, Hong Kong, Shanghai, Sydney | Python, C++, Linux | Sep 01, 2026 | [Apply](https://www.tower-research.com/open-positions/?gh_jid=8168750) |
| Bracco | Data Analyst Intern | Data & ML/AI | ITA - Milano - Via Egidio Folli | Python, SQL, Databricks | Sep 01, 2026 | [Apply](https://bracco.wd103.myworkdayjobs.com/braccocareers/job/ITA---Milano---Via-Egidio-Folli/Data-Analyst-Intern_JR100349) |
| Stryker | Embedded Software Engineering Co-Op Student | Software | Carrigtwohill, Ireland | Python, C++ | Sep 01, 2026 | [Apply](https://stryker.wd1.myworkdayjobs.com/StrykerCareers/job/Carrigtwohill-Ireland/Embedded-Software-Engineering-Co-Op-Student_R572136) |
| Pluralis Research | Research Engineer Intern | Software | Australia | Python, PyTorch, AWS, GCP | Aug 31, 2026 | [Apply](https://jobs.ashbyhq.com/pluralis-research/8860e7ec-90f0-4fc8-bd83-90063137ec45) |
| Stripe | Software Engineer, Intern | Software | London | Java, JavaScript, Scala, Ruby | Aug 31, 2026 | [Apply](https://stripe.com/jobs/search?gh_jid=8130867) |
| Epic Games | Web Engineer Intern | Software | London,England,United Kingdom | TypeScript, JavaScript, React, Next.js | Aug 28, 2026 | [Apply](https://epicgames.com/careers/jobs/6163851004?gh_jid=6163851004) |
| Hitachi Energy | Internship – Full-stack Software Engineer | Software | Krakow, Lesser Poland, Poland | Java, TypeScript, Kotlin, React | Aug 26, 2026 | [Apply](https://hitachi.wd1.myworkdayjobs.com/hitachi/job/Krakow-Lesser-Poland-Poland/Internship---Full-stack-Software-Engineer_R0142565-1) |
| Phlair | Working Student / Intern – Control Team (Systems & Data Infrastructure) (f/m/d) | Data & ML/AI | München | Python, PostgreSQL | Aug 24, 2026 | [Apply](https://jobs.ashbyhq.com/phlair/8021960b-1e19-406b-99c2-bac26fbe2c86) |
| Western Digital | Intern - AI Information Technology (Studying Master's and Bachelor Degree) | Data & ML/AI | BangPa-in +2 more | Python, Java, C++, C# | Aug 24, 2026 | [Apply](https://jobs.smartrecruiters.com/WesternDigital/744000145156358) |
| Garda Capital Partners | Software Engineer Intern (AI Internal Tools) | Data & ML/AI | Geneva +5 more | No skills listed | Aug 18, 2026 | [Apply](https://job-boards.greenhouse.io/gardacp/jobs/6146408004) |
| Stripe | Software Engineer, Intern (Summer or Winter) | Software | Dublin | Java, JavaScript, Scala, Ruby | Aug 17, 2026 | [Apply](https://stripe.com/jobs/search?gh_jid=8097801) |
| Tower Research Capital | Quantitative Research Internship - 6 Months, Central Execution Research | Quant | London | Python, C++, Rust | Aug 12, 2026 | [Apply](https://www.tower-research.com/open-positions/?gh_jid=8113986) |

<a id="drop-radar"></a>

## 📅 Drop Radar — when companies usually post for Summer 2027

Stop refreshing career pages. 🎯 = the employer's **own posted date**, read from their careers API. (We may have discovered the role after it went live — the date is the employer's, not our discovery time.) The rest are typical opening **months**, hand-checked against each company's careers page and public recruiting guides. ✅ = already live in the list above.

> **Heads up:** companies trend *earlier* every cycle, and "~Aug" is a month, not a day. Treat "expected" as when to **start watching**, and "rolling" companies as worth checking year-round.

| Company | Typical opening | Expected this cycle | Status |
|---|---|---|---|
| 3M | ~Sep | ~Sep · any day now | ⏳ waiting |
| Adobe | ~Sep | ~Sep · any day now | ⏳ waiting |
| Airbnb | ~Sep | ~Sep · any day now | ⏳ waiting |
| AMD | ~Sep | ~Sep · any day now | ⏳ waiting |
| Anduril Industries | ~Sep | ~Sep · any day now | ⏳ waiting |
| Applied Intuition | ~Sep | ~Sep · any day now | ⏳ waiting |
| Asana | ~Sep | ~Sep · any day now | ⏳ waiting |
| Aurora | ~Sep | ~Sep · any day now | ⏳ waiting |
| Bloomberg | ~Sep | ~Sep · any day now | ⏳ waiting |
| Blue Origin | ~Sep | ~Sep · any day now | ⏳ waiting |
| Boeing | ~Sep | ~Sep · any day now | ⏳ waiting |
| Booz Allen Hamilton | ~Sep | ~Sep · any day now | ⏳ waiting |
| Boston Scientific | ~Sep | ~Sep · any day now | ⏳ waiting |
| Carvana | ~Sep | ~Sep · any day now | ⏳ waiting |
| Caterpillar | ~Sep | ~Sep · any day now | ⏳ waiting |
| Chewy | ~Sep | ~Sep · any day now | ⏳ waiting |
| Cloudflare | ~Sep | ~Sep · any day now | ⏳ waiting |
| Comcast | ~Sep | ~Sep · any day now | ⏳ waiting |
| Confluent | ~Sep | ~Sep · any day now | ⏳ waiting |
| Coupang | ~Sep | ~Sep · any day now | ⏳ waiting |
| CrowdStrike | ~Sep | ~Sep · any day now | ⏳ waiting |
| Dell Technologies | ~Sep | ~Sep · any day now | ⏳ waiting |
| Discord | ~Sep | ~Sep · any day now | ⏳ waiting |
| Dropbox | ~Sep | ~Sep · any day now | ⏳ waiting |
| Elastic | ~Sep | ~Sep · any day now | ⏳ waiting |
| Electronic Arts | ~Sep | ~Sep · any day now | ⏳ waiting |
| Epic Games | ~Sep | ~Sep · any day now | ⏳ waiting |
| Fastly | ~Sep | ~Sep · any day now | ⏳ waiting |
| Ford | ~Sep | ~Sep · any day now | ⏳ waiting |
| General Motors | ~Sep | ~Sep · any day now | ⏳ waiting |

_293 companies on the [full radar](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/#radar). **171** dated from our own live observations 🎯 (this grows every cycle). "~Aug" = hand-verified typical month, not a promise of the day; "rolling" = posts year-round; "waiting" = not seen in our tracked feeds yet, not a guarantee it isn't out somewhere else._

<details>
<summary><strong>Recently closed</strong> — 6 roles that left the list in the last 14 days</summary>

_Why each one left is in the last column, because the two reasons carry different evidence. **Gone from feed** = two consecutive complete reads of the employer's board no longer returned it (strong, but not the employer telling us directly). **Out of scope** = still posted, but it no longer passes our filters — our call, not theirs. **Not recorded** = closed before we started tracking the reason._

| Company | Role | Cycle | Closed | Why |
|---|---|---|---|---|
| Brookfield | 2027 Summer MBA Intern, Investments, Infrastructure AI | Summer 2027 | 2026-09-24 | gone from feed |
| WorldQuant | Quantitative Research Internship 2027 | Summer 2027 | 2026-09-24 | out of scope |
| Schroders | 2027 Schroders Capital Infrastructure - Product Strategy Internship Programme | Summer 2027 | 2026-09-22 | out of scope |
| Ontario Teachers' Pension Plan | Intern- Investments, Infrastructure & Natural Resources (May 2027- 4 Month Contract) | Summer 2027 | 2026-09-22 | out of scope |
| Geotab | Hardware Developer Intern (Summer/May 2027, 12 Months) | Summer 2027 | 2026-09-16 | gone from feed |
| Intact | Developer DevOPS - 4 months Co-op Internship | Summer 2027 | 2026-09-16 | out of scope |

</details>

---

## Hiring timeline

Internships posted per week, from each role's real published date - redrawn automatically on every run. When this line takes off, recruiting season is open:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/trends-dark.svg">
  <img alt="Internships posted per week, drawn from real published dates" src="docs/trends-light.svg">
</picture>

## How it stays current

A small Python engine reads public company hiring feeds directly, keeps the roles that match the scope above, de-duplicates across sources, records each role's published date once (so it never shifts), and regenerates this page through GitHub Actions. It polls every company concurrently (async) with retry/backoff and per-host rate limits. The full source is in this repo.

_Engine (last run): 4,416 of 4,891 registered boards returned successfully across 12 ATS platforms (97% of boards attempted, 90% of the full registry) · completed in 1063.8s · 575 board(s) returned a capped result set, so their roles were not eligible to be closed this run · employer or source-derived date on 100% of open roles._

## How this list is built

[METHODOLOGY.md](METHODOLOGY.md) documents exactly what every label claims — what separates a stated cycle from an inferred one, how sponsorship flags are detected, how a role gets closed, and which limitations are known. Anything on this page that doesn't match the code is a bug worth reporting.

## Contributing

Adding a company takes one line, see [CONTRIBUTING.md](CONTRIBUTING.md), or just [open a request](../../issues/new?template=add-company.yml) with the board URL. **Spotted something wrong?** [Report the exact field](../../issues/new?template=wrong-data.yml) — wrong country, wrong cycle, closed role, bad sponsorship flag. Those reports usually fix a rule, which fixes every other role too.

Also here: [PRIVACY.md](PRIVACY.md) (what the email list stores — an address and nothing else) · [SECURITY.md](SECURITY.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [MIT licensed](LICENSE).

Built by one student with AI assistance, in the open. The part that matters isn't who typed it — it's that the rules, the tests, and every run's output are all public and checkable.

## Note on dates

The **Posted** column shows when a role was published, with the newest at the top. I pull the posting date straight from each job portal, but a lot of them don't expose one publicly, so those rows show a dash (—) for now instead of a guessed date. The ones that do publish a date are dated. Know the real date for a dashed role? Open a PR and I'll merge it.

Roles can close at any time, so always confirm on the company's own site before applying.
