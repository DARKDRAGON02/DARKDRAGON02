<div align="center">

# Kishan S

**CSE '27 · PES University, Bengaluru**

*I build below the framework — then ship it to real users.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kishan_S-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kishan-s-72b250334/)
[![Email](https://img.shields.io/badge/Email-kishan.sangram%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kishan.sangram@gmail.com)

</div>

---

Most student portfolios are the same MERN CRUD app four times. Mine isn't, so here's the honest version of what I actually do:

I like the layer underneath the one everybody else works at. My container runtime is written in C against raw `clone()` and Linux namespaces, with a kernel module that accounts RSS and kills the process when it blows its limit. My AI relay encrypts in the browser with AES-256-GCM and hands the server nothing but ciphertext, so the "trust us" box doesn't have to exist. Both of those turned out to be the most fun I've had writing software.

The other half of my time is shipping things people actually open — including a booking system built for a working maternity clinic, live in production.

---

## What I work on

**Systems & low level.** Linux namespaces, `clone()`, kernel modules, memory accounting, process supervision. Written in C and Linux system calls — not YAML around somebody else's runtime.

**Applied security.** Authenticated encryption with AES-256-GCM through the Web Crypto API, zero-knowledge relay design, JWT auth flows. I care about what the server *cannot* see, not just what it validates.

**Full-stack delivery.** React / Next.js / Vite front ends, Node and Express APIs, cloud deploys. I finish projects instead of collecting half-built repos.

---

## Featured projects

| Project | What it actually is | What it proves |
|---|---|---|
| **[Secure-Vault-AI](https://github.com/DARKDRAGON02/Secure-Vault-AI)** | End-to-end encrypted relay for AI prompts. The client encrypts with AES-256-GCM; the Node relay only ever handles ciphertext. | Threat modelling, browser crypto, API design |
| **[container-runtime-monitor](https://github.com/DARKDRAGON02/container-runtime-monitor)** | A container runtime in C: PID/UTS/mount isolation via `clone()`, a supervisor CLI, and a kernel module that samples RSS and kills the process past its hard limit. | Systems programming, kernel modules, real resource control |
| **[swara-maternity-clinic](https://github.com/DARKDRAGON02/swara-maternity-clinic)** | Appointment booking built for a real clinic — Express API, Vite + React + Tailwind UI, zero-login email-driven admin so staff don't manage passwords. **Live →** [swara-maternity-clinic.vercel.app](https://swara-maternity-clinic.vercel.app) | Working with a real client, scoping, shipping |
| **[E-Commerce](https://github.com/DARKDRAGON02/E-Commerce)** | MERN storefront with Firebase Auth, a Cloudinary media pipeline, cart and admin dashboard, responsive Tailwind UI. | Full-stack breadth, auth, third-party integration |

### Also worth a look

- **[suspended-sediment-particle-size-prediction](https://github.com/DARKDRAGON02/suspended-sediment-particle-size-prediction)** — benchmarked Random Forest vs SVR vs XGBoost with reproducible runs, feature importance and an R² comparison.
- **[flow-timeout-manager](https://github.com/DARKDRAGON02/flow-timeout-manager)** — SDN experiment on OpenFlow rule lifecycles using a Ryu controller and Mininet topology.

---

## Toolbox

| | |
|---|---|
| **Languages** | C · Python · TypeScript · JavaScript |
| **Systems** | Linux namespaces · `clone()` · kernel modules · process supervision · SDN (OpenFlow, Ryu, Mininet) |
| **Security** | AES-256-GCM · Web Crypto API · JWT · static analysis (pylint, flake8, bandit) |
| **Web** | React · Next.js · Vite · Node.js · Express · Tailwind CSS · MongoDB · Firebase Auth · Cloudinary |
| **ML / Data** | scikit-learn · XGBoost · pandas · NumPy · Jupyter |
| **Tooling** | Git · GitHub Actions · Vercel |

---

<div align="center">

**Open to 2027 new-grad and internship roles** in systems, security, or product engineering.

I also work in shared codebases — my PRs are on `se-mini-project-t16/railway-reservation-system` (JWT auth, ownership-checked e-ticket generation).

</div>
