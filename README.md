<div align="center">

# 🍁 Canada & Japan Tech Internships

**A self-updating engine that tracks tech internships so you don't have to.**

[![CI](https://img.shields.io/github/actions/workflow/status/parkerhayashi/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/ci.yml?branch=main&label=tests&style=flat-square&color=3fb950)](https://github.com/parkerhayashi/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/actions/workflows/ci.yml)&nbsp;[![Open roles](https://img.shields.io/badge/dynamic/json?label=open%20roles&query=open_total&url=https%3A%2F%2Fparkerhayashi.github.io%2FAutomated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships%2Fapi%2Fstats.json&color=2f81f7&style=flat-square)](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/)&nbsp;![Updates](https://img.shields.io/badge/updates-every%2030%20min-3fb950?style=flat-square)&nbsp;[![RSS](https://img.shields.io/badge/RSS-subscribe-e67e22?style=flat-square)](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/feed.xml)

### 79 open roles (54 listed below) · 40 new this week

4,607 employers tracked · data as of Sep 20, 2026 at 14:21 UTC

_39 have a cycle the employer stated · 40 are recent postings whose cycle isn't stated (listed separately, never mixed in)._

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
| ⚙️ **An engine, not a spreadsheet** | 4,866 job-board endpoints (4,607 distinct employers; some run more than one board) polled every 30 minutes across 12 ATS platforms. Full source and tests in this repo. |

## Scope

| | |
|---|---|
| **Roles** | Software, Data & ML/AI, Quant, Product (PM / TPM), VC, and Product Design / UX internships — not marketing, recruiting, or general business |
| **Region** | Canada & Japan |
| **Cycles** | Summer 2027 |

## About

This fork of the internship engine tracks software, data, ML, quant, product (PM/TPM), venture capital, and product-design internships and co-ops located in Canada and Japan for Summer 2027, plus recent postings that don't name a cycle.

Use it to spot roles early and apply before they fill up. Being first genuinely helps.

## Where this is going

I'm building this in the open and adding to it as it grows.

**Recently shipped:** the Drop Radar · auto-detected sponsorship flags · the live dashboard

**Next up:** personalized alerts (pick your categories) · per-company hiring pages · a ghost-posting detector

If it helps you, a star means a lot and tells me to keep going.

## How to use

<details>
<summary><b>Reading the table — flags, dates, and the cycle split</b> (click to expand)</summary>

- Roles are grouped by cycle below - **newest posting on top, oldest at the bottom.**
- A cycle section holds only roles whose **employer stated that cycle** - in the title, or in the posting's own text. Postings that name no cycle anywhere are in *Recently posted — cycle not stated* further down, with **no cycle guessed for them**. Same quality bar, different amount of evidence.
- The **Posted** column is the date the company published the role.
- **_(3 openings)_ after a role title** = the employer has that many separate live requisitions for the same job, in the same place, for the same cycle. They're all real and each takes its own application, so they're linked individually (**Apply**, then **#2**, **#3**) instead of repeating the row. Counts still count requisitions, and the CSV export is never grouped.
- **🆁 after a company name** = **this role is remote** — the posting's own location or title says so. It marks the role on that row, not the whole company.
- **Flags after a role title:** 🇨🇦 = requires Canadian citizenship, permanent residency, or a security clearance · 🇯🇵 = requires Japanese citizenship or nationality · 🛂 = the posting says it won't sponsor a work permit · 🆕 = spotted in the last 48 hours. Sponsorship flags are detected automatically from each job description - treat them as a strong hint and confirm on the posting.

- Track your applications with [`data/internships.csv`](data/internships.csv) (opens in Excel / Google Sheets).
- Missing a company? Adding one takes a single line, see [CONTRIBUTING.md](CONTRIBUTING.md).

</details>

---

## Summer 2027  (27 employer-stated)

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Amazon | Software Development Engineer Intern - Summer 2027 (CAN) 🆕 | Software | Vancouver, International | Python, Java, C++, C# | Sep 18, 2026 | [Apply](https://www.amazon.jobs/en/jobs/10553947/software-development-engineer-intern-summer-2027-can) |
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
| Ontario Teachers' Pension Plan | Intern- Investments, Infrastructure & Natural Resources (May 2027- 4 Month Contract) | Software | Toronto, Canada | No skills listed | Aug 21, 2026 | [Apply](https://otppb.wd3.myworkdayjobs.com/OntarioTeachers_Careers/job/Toronto-Canada/Intern--Investments--Infrastructure---Natural-Resources--May-2027--4-Month-Contract-_7163) |
| Georgian Partners Growth | AI/ML Engineer Intern (2027) | Data & ML/AI | Toronto Headquarters | Python, PyTorch, TensorFlow, scikit-learn | Jul 14, 2026 | [Apply](https://jobs.ashbyhq.com/georgian/2ae71a4b-dd9d-4068-8ef2-81351ee74cab) |
| Squarepoint Capital | Intern Software Developer - Montreal - 2027 | Software | Montreal | Python, Java, C++, Rust | May 07, 2026 | [Apply](https://www.squarepoint-capital.com/open-opportunities?id=7905463&gh_jid=7905463) |

## Recently posted — cycle not stated  (26 roles)

These postings never name a cycle — not in the title, not in the posting text — so neither do we. They're recent tech internships (posted within the last few weeks), often exactly the early drops worth applying to first; we just can't tell you which cycle they're for, and we'd rather say so than guess. The moment a posting's own text states a cycle, the role moves up into that section automatically.

| Company | Role | Category | Location | Skills | Posted | Apply |
|---|---|---|---|---|---|---|
| Autodesk | Product Management Intern, Stagiaire Gestion de Produit 🆕 | PM | Montreal, QC, CAN | LLMs | Sep 19, 2026 | [Apply](https://autodesk.wd1.myworkdayjobs.com/uni/job/Montreal-QC-CAN/Product-Management-Intern--Stagiaire-Gestion-de-Produit_26WD101135-1) |
| Genesys | Software Developer, Intern (Genesys Cloud) 🆕 | Software | Toronto (Flexible) | TypeScript, JavaScript, Vue, AWS | Sep 18, 2026 | [Apply](https://genesys.wd1.myworkdayjobs.com/Genesys/job/Toronto-Flexible/Software-Developer--Intern--Genesys-Cloud-_JR112244-1) |
| Genesys | Software Developer Full-Stack Intern, AI Scoring, Evaluations and Surveys 🆕 | Data & ML/AI | Toronto (Flexible) | Python, Java, TypeScript, JavaScript | Sep 18, 2026 | [Apply](https://genesys.wd1.myworkdayjobs.com/Genesys/job/Toronto-Flexible/Software-Developer-Full-Stack-Intern--AI-Scoring--Evaluations-and-Surveys_JR112168-1) |
| Genesys | Software Developer Intern, Predictions Data & Decision Science 🆕 | Data & ML/AI | Toronto (Flexible) | Python, Java, C++, C# | Sep 18, 2026 | [Apply](https://genesys.wd1.myworkdayjobs.com/Genesys/job/Toronto-Flexible/Software-Developer-Intern--Predictions-Data---Decision-Science_JR112176-1) |
| Keenfinity | Research Intern – AI-Based Audio Optimization 🆕 | Data & ML/AI | Eindhoven +2 more | Python, C++, MATLAB | Sep 18, 2026 | [Apply](https://jobs.smartrecruiters.com/Keenfinity/744000150347490) |
| Bosch | 【MA】Internship Regional Product Manager in Aftermarket Asia Pacific South | PM | Bosch Corporation_Internship +2 more | Python, SQL | Sep 18, 2026 | [Apply](https://jobs.smartrecruiters.com/BoschGroup/744000150296334) |
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
| Epic Games | Machine Learning Intern | Data & ML/AI | Montreal,Quebec,Canada | Python, C++, C#, PyTorch | Aug 07, 2026 | [Apply](https://epicgames.com/careers/jobs/6138140004?gh_jid=6138140004) |

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

_274 companies on the [full radar](https://parkerhayashi.github.io/Automated-List-Of-Summer-2027-and-Fall-2026-Tech-Internships/#radar). **147** dated from our own live observations 🎯 (this grows every cycle). "~Aug" = hand-verified typical month, not a promise of the day; "rolling" = posts year-round; "waiting" = not seen in our tracked feeds yet, not a guarantee it isn't out somewhere else._

<details>
<summary><strong>Recently closed</strong> — 3 roles that left the list in the last 14 days</summary>

_Why each one left is in the last column, because the two reasons carry different evidence. **Gone from feed** = two consecutive complete reads of the employer's board no longer returned it (strong, but not the employer telling us directly). **Out of scope** = still posted, but it no longer passes our filters — our call, not theirs. **Not recorded** = closed before we started tracking the reason._

| Company | Role | Cycle | Closed | Why |
|---|---|---|---|---|
| Geotab | Hardware Developer Intern (Summer/May 2027, 12 Months) | Summer 2027 | 2026-09-16 | gone from feed |
| Intact | Developer DevOPS - 4 months Co-op Internship | Summer 2027 | 2026-09-16 | out of scope |
| Royal Bank of Canada | 2027 Summer - GRM, AI Innovation - Business Analyst Intern (4 Months) | Summer 2027 | 2026-09-09 | gone from feed |

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

_Engine (last run): 4,523 of 4,866 registered boards returned successfully across 12 ATS platforms (99% of boards attempted, 93% of the full registry) · completed in 716.8s · 618 board(s) returned a capped result set, so their roles were not eligible to be closed this run · employer or source-derived date on 100% of open roles._

## How this list is built

[METHODOLOGY.md](METHODOLOGY.md) documents exactly what every label claims — what separates a stated cycle from an inferred one, how sponsorship flags are detected, how a role gets closed, and which limitations are known. Anything on this page that doesn't match the code is a bug worth reporting.

## Contributing

Adding a company takes one line, see [CONTRIBUTING.md](CONTRIBUTING.md), or just [open a request](../../issues/new?template=add-company.yml) with the board URL. **Spotted something wrong?** [Report the exact field](../../issues/new?template=wrong-data.yml) — wrong country, wrong cycle, closed role, bad sponsorship flag. Those reports usually fix a rule, which fixes every other role too.

Also here: [PRIVACY.md](PRIVACY.md) (what the email list stores — an address and nothing else) · [SECURITY.md](SECURITY.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [MIT licensed](LICENSE).

Built by one student with AI assistance, in the open. The part that matters isn't who typed it — it's that the rules, the tests, and every run's output are all public and checkable.

## Note on dates

The **Posted** column shows when a role was published, with the newest at the top. I pull the posting date straight from each job portal, but a lot of them don't expose one publicly, so those rows show a dash (—) for now instead of a guessed date. The ones that do publish a date are dated. Know the real date for a dashed role? Open a PR and I'll merge it.

Roles can close at any time, so always confirm on the company's own site before applying.
