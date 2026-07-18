# Repositioning Audit: SRE/Platform → Software Engineer

Branch: `swe-repositioning`
Scope: `index.html` only (the site's single served file).

## 1. Change Table

| Section | OLD text (verbatim) | NEW text (verbatim) |
|---|---|---|
| `<head>` meta (grouped) | `<title>Matthew Fitzgerald</title>` (no meta description, no OG/Twitter tags existed) | `<title>Matthew Fitzgerald \| Software Engineer</title>`<br>`<meta name="description" content="Matthew Fitzgerald is a Software Engineer working in Python, TypeScript, and ML systems, with a background in platform infrastructure.">`<br>`<meta property="og:title" content="Matthew Fitzgerald \| Software Engineer">`<br>`<meta property="og:description" content="Software Engineer working in Python, TypeScript, and ML systems, with a background in platform infrastructure.">`<br>`<meta property="og:type" content="website">`<br>`<meta property="og:url" content="https://matthewfitzgerald.net">`<br>`<meta name="twitter:card" content="summary">`<br>`<meta name="twitter:title" content="Matthew Fitzgerald \| Software Engineer">`<br>`<meta name="twitter:description" content="Software Engineer working in Python, TypeScript, and ML systems, with a background in platform infrastructure.">` |
| Hero tagline | `Platform / Site Reliability Engineer \| Kubernetes, Multi-Cloud Infrastructure, CI/CD \| Reliability & Observability` | `Software Engineer \| Python, TypeScript, ML Systems` |
| Hero sub-line | `Hands-on experience operating production Kubernetes, multi-cloud infrastructure, and CI/CD at scale, with a focus on observability and automating away toil.` | `I build APIs, data pipelines, and ML systems in Python and TypeScript, with a platform engineering background in Kubernetes, Terraform, and multi-cloud infrastructure.` |
| Experience: order | EarthCam listed third (after CNS, before Dfinitiv) | EarthCam listed first, then CNS, then Dfinitiv |
| Experience: EarthCam title | `Junior Fullstack Engineer at EarthCam` | `Junior Full Stack Engineer at EarthCam` |
| Experience: EarthCam perf bullet | `Re-architected the data-fetching layer of a core customer-facing component around asynchronous API calls, reducing fetch overhead for a 3–5x improvement in load time` | `Re-architected the data-fetching layer of a core customer-facing component around asynchronous API calls, cutting load time from 15,000+ ms to 2,000-3,000 ms, a 3-5x improvement` |
| Experience: CNS title | `Platform Engineer at Cognitive Network Solutions` | `Software Engineer (Platform & ML Infrastructure) at Cognitive Network Solutions` |
| About Me: para 1 | `I'm a platform and site reliability engineer with hands-on experience operating production Kubernetes, multi-cloud infrastructure, and CI/CD at scale. I care most about service reliability, observability, and automating away toil.` | `I'm a software engineer who builds APIs, data pipelines, and ML systems in Python and TypeScript. At EarthCam, I re-architected the data-fetching layer of a core customer-facing component around asynchronous API calls, cutting load time from 15,000+ ms to 2,000-3,000 ms, a 3-5x improvement, and delivered new pages and features across the stack in TypeScript and Node.js.` |
| About Me: para 2 | `At Cognitive Network Solutions, I built and maintained Kubernetes platforms with Helm deployments, Ingress controllers, and namespace isolation for reproducible, reliable service delivery, on multi-cloud infrastructure I designed and deployed across GCP and Azure with Terraform. I engineered CI/CD pipelines with GitLab runners while embedding secrets management and least-privilege IAM.` | `On my own time, I build end-to-end ML systems: a fine-tuned LLM served behind a streaming FastAPI inference API with an automated evaluation gate, a ReAct-style agent with multi-turn memory and live reasoning-step streaming, and a feature engineering pipeline for financial transaction data with point-in-time correct serving and unit tests covering ingestion through serving.` |
| About Me: para 3 | `I established the monitoring and observability layer — Prometheus, structured logging, and liveness/readiness probes with SLI/SLO instrumentation — that reduced time-to-detection and kept services reliable in production.` | `At Cognitive Network Solutions, I developed and secured databases with role-based access controls, integrated them into microservices, and provisioned GPU node pools and inference auto-scaling with CUDA and MLflow for ML workloads. I also run the infrastructure my software ships on: Kubernetes platforms with Helm and Ingress, multi-cloud infrastructure on GCP and Azure with Terraform, and CI/CD pipelines with GitLab runners.` |
| About Me: para 4 | `On the ML infrastructure side, I provisioned GPU node pools and inference auto-scaling with CUDA and MLflow — reliability and platform work for ML systems, not model development. Previously at Dfinitiv, I built cloud-native data pipelines on AWS and GCP that cut processing time by over 60%.` | `Previously at Dfinitiv, I built cloud-native data pipelines on AWS and GCP that cut processing time by over 60%.` |
| About Me: para 5 (closing) | `I'm looking for an Associate SRE role on cloud-native, container-based platforms, where I can keep production systems reliable and automate away toil.` | `I'm looking for Software Engineer and Backend Engineer roles where I can build production software, backed by the platform experience to run it reliably.` |
| Skills: category structure | 7 categories: Reliability & Observability, Containers & Orchestration, Infrastructure as Code & CI/CD, Cloud, Linux & Networking, GPU / ML Infrastructure, Programming & Scripting | 5 categories in resume order: Python (Primary), Other Languages, ML & Data, Cloud & DevOps, AI-Assisted Engineering |
| Skills: Python (Primary) | (did not exist as a category; Python was one tag under "Programming & Scripting") | New category, first position: Python, FastAPI, SQLAlchemy, APScheduler, Pandera, Prefect, boto3, psycopg2, pymongo, Selenium, Playwright |
| Skills: Other Languages | `Python, Go, Bash, Java, C++, SQL (PostgreSQL), NoSQL (MongoDB)` (under "Programming & Scripting") | `TypeScript/Node.js, Go, SQL, MongoDB, Java, C++, Bash` |
| Skills: ML & Data | Split across "GPU / ML Infrastructure" (CUDA, MLflow, GPU Node-Pool Provisioning, Inference Auto-Scaling) with no ML libraries listed | Consolidated: MLX / mlx-lm, Hugging Face, LoRA Fine-Tuning, MLflow, CUDA, River (Online ML), sentence-transformers, ChromaDB, BM25 / Hybrid Retrieval, Redis, GPU Node-Pool Provisioning, Inference Auto-Scaling |
| Skills: Cloud & DevOps | Split across 5 separate categories (Reliability & Observability, Containers & Orchestration, IaC & CI/CD, Cloud, Linux & Networking) | Consolidated into one 4th-position category, same tags, no tags removed |
| Skills: AI-Assisted Engineering | (did not exist) | New category, 5th position: Claude Code Agentic Workflows, MCP Server Development, PR-Based AI Review Loops |
| Projects: order | financial-sentiment-llm, ml-platform, ml-drift-monitor, rag-pipeline, llm-agent, llm-guardrails | financial-sentiment-llm, llm-agent, ml-data-pipeline, ml-drift-monitor, ml-platform, rag-pipeline, llm-guardrails |
| Projects: ml-data-pipeline card | (did not exist on site) | New card: "ML Data Pipeline" — `End-to-end feature engineering pipeline for financial transaction data: schema validation, windowed aggregations enforcing point-in-time correctness, a versioned offline feature store, and a FastAPI serving layer, with unit tests covering ingestion, features, store, and serving.` Libraries: FastAPI, Pandera, Prefect, SQLAlchemy, PostgreSQL, Redis, pandas. Links to `https://github.com/matthew-fitzgerald123/ml-data-pipeline` |
| Projects: ml-drift-monitor description | `Real-time drift detection service using ADWIN on live inference streams, with scheduled retraining, webhook alerting, and automatic model promotion via the registry.` | `Data drift detection service using ADWIN with an automated retraining pipeline, monitoring model inputs in production and triggering retraining on distribution shift.` |

## 2. Parity Check

| # | Rule | Where satisfied |
|---|---|---|
| 1 | Headline is "Software Engineer", identity labels (SRE, Site Reliability, Platform Engineer, MLOps Engineer, reliability, infrastructure engineer) removed from headline | Hero tagline (`index.html`, hero section): now `Software Engineer \| Python, TypeScript, ML Systems`. Residue scan below confirms no banned identity terms remain in the headline. |
| 2 | Bio leads with software (Python, TypeScript/Node.js, FastAPI, APIs, data pipelines, ML systems); infra in one supporting sentence with "I also run the infrastructure my software ships on" framing | About Me section, paragraph 1 (software lead) and paragraph 3 (contains the exact sentence "I also run the infrastructure my software ships on: Kubernetes platforms with Helm and Ingress, multi-cloud infrastructure on GCP and Azure with Terraform, and CI/CD pipelines with GitLab runners.") |
| 3 | Experience order EarthCam → CNS → Dfinitiv; CNS title "Software Engineer (Platform & ML Infrastructure)"; EarthCam perf bullet uses specified load-time wording | Resume/Experience section: EarthCam block moved first, CNS title updated, EarthCam bullet text matches specification exactly |
| 4 | Projects: financial-sentiment-llm, llm-agent, ml-data-pipeline, ml-drift-monitor featured first in that order, GitHub links, craft-forward descriptions; ml-drift-monitor uses specified description; rootfall/kubefall/heapfall not featured | Projects section: cards reordered to that exact sequence, all four have `View Repository` GitHub links, ml-drift-monitor description matches specification verbatim. rootfall/kubefall/heapfall were never present on the site (confirmed via residue scan), so the "move or remove" instruction is N/A. |
| 5 | Skills mirror resume order: Python (primary), Other Languages, ML & Data, Cloud & DevOps, AI-Assisted Engineering line | Skills section: five categories in that exact order, Other Languages tag set matches the specified list verbatim, AI-Assisted Engineering line added with the three specified items |
| 6 | No em dashes in new copy | Verified via `grep` for the em dash character (—) across `index.html`: zero hits |
| 7 | Truthful copy; no invented metrics/employers/titles/dates; unresolved factual claims flagged, not silently rewritten | ml-data-pipeline description was written from the project's actual README/requirements.txt (verified locally, not invented). CNS and Dfinitiv bullet content left untouched since only title/order changes were specified. See Flags section below for items left as-is. |
| 8 | `<title>`, meta description, OG/Twitter tags updated to Software Engineer positioning | `<head>`: title changed, meta description added, og:title/og:description/og:type/og:url added, twitter:card/title/description added (none existed before) |

## 3. Flags

Nothing found that conflicts with the new positioning and was left unchanged for factual reasons requiring your decision. Specifically:

- **CNS experience bullets** (6 bullets under "Software Engineer (Platform & ML Infrastructure)") still read as pure platform/infra work (Kubernetes, Terraform, CI/CD, GPU provisioning). Only the role title and section order were specified for change, so the bullet content itself is untouched. This is consistent with the "differentiator, not headline" framing since it lives in the experience section, not the headline, but flagging in case you want the bullets themselves reworded to foreground any software-engineering angle of that role.
- **Dfinitiv title/dates** ("Software Engineer, Intern at Dfinitiv.io", Summer 2023, 2024) were already SWE-aligned and unchanged.

No other factual claims were found that conflict with the new positioning.

## 4. Residue Scan

Case-insensitive search of final `index.html` for the specified terms:

| Term | Hits | Disposition |
|---|---|---|
| `SRE` | 0 | Clean |
| `site reliability` | 0 | Clean |
| `platform engineer` | 1 (substring match inside "platform engineer**ing** background") | **Stays.** Hero sub-line: "...with a platform engineering background in Kubernetes, Terraform, and multi-cloud infrastructure." This is a descriptive noun phrase in a supporting sentence ("platform engineering background"), not an identity label ("I am a Platform Engineer") in the headline. Rule 1 prohibits headline identity-label usage; this is the differentiator clause immediately below the headline, matching the intent of rule 2. |
| `MLOps` | 0 | Clean |
| `reliability engineer` | 0 | Clean |
| `rootfall` | 0 | Clean (never featured on the site to begin with; rule 4's "move or remove" is N/A) |

Additional note: the word "reliability" (not on the banned list, but adjacent) still appears twice, both inside untouched CNS experience bullets ("...improved service reliability", "...tuning for both cost and reliability"). These are factual descriptions of past work, not identity labels, and fall under the Flags item above.
