<h1 align="center">Hi, I'm Wiza 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Backend+Developer;Large-Scale+Systems;Django+%2B+PostgreSQL;Lusaka%2C+Zambia" alt="Backend Developer · Large-Scale Systems · Django + PostgreSQL · Lusaka, Zambia"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Computer%20Science-ZCAS%20University-2b6cb0?style=flat-square" alt="Computer Science, ZCAS University"/>
  <img src="https://img.shields.io/badge/Based%20in-Lusaka%2C%20Zambia-informational?style=flat-square" alt="Lusaka, Zambia"/>
  <img src="https://img.shields.io/badge/Focus-Backend%20%26%20Large--Scale%20Systems-2F81F7?style=flat-square" alt="Focus: Backend and large-scale systems"/>
</p>

---

### About

**I care more about the engine than the paint job.**

With cars, that means turbos, superchargers, and why one engine pulls harder than another.
With software, it's the same question: what is actually happening underneath? How does a
database keep two companies' data apart? What happens when a request is retried halfway
through? Why does a system that works for ten users fall over at ten thousand?

I'm a Computer Science student at ZCAS University, working toward backend engineering
and large-scale systems. I build the parts most people never see: data models,
transactions, tenant isolation, and the tests that prove they hold.

### Tools I use

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,django,postgres,docker,githubactions,linux&theme=dark" alt="Python, Django, PostgreSQL, Docker, GitHub Actions, Linux"/>
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,nextjs,react,flutter&theme=dark" alt="TypeScript, Next.js, React, Flutter"/>
</p>

### What I'm building

**ZAMHRMS** is a multi-tenant HR and payroll platform for Zambian businesses. It covers
employees, attendance, leave, recruitment, and payroll with PAYE, NAPSA and NHIMA.

📌 See the **[zamhrms case study](https://github.com/Uncle-za/zamhrms)** for the
architecture, the decisions behind it, and a build log. The source is private because it is
a commercial product; the case study shows *how* it is built, not a copy of it.

| Engineering problem | How I solved it |
|---|---|
| 🔒 **Keeping companies' data apart** | PostgreSQL row-level security on every table, tested against a second tenant's data |
| 🔁 **Retries that must not double-pay** | Idempotency keys claimed atomically in the database, safe across multiple servers |
| 🧾 **Tax rules that change every budget** | PAYE, NAPSA and NHIMA stored as versioned, dated rate tables, not hard-coded numbers |
| 🪪 **Searching encrypted national IDs** | AES-256-GCM encryption with an HMAC blind index |
| ✅ **Proving it works** | 870+ automated tests; CI runs linting, type checks, secret scanning and dependency audits on every pull request |

### Other work

| Project | What it is |
|---|---|
| 📱 **[My Store](https://github.com/Uncle-za/My_store_app)** | Flutter shopping app with a catalogue, cart, checkout and an order status timeline (group assignment) |

### What I'm taking apart next

Networking and distributed systems: how services stay correct when the network, a disk,
or another service fails. Projects from that work will appear here.

### Let's talk

I'm open to backend and infrastructure internships and graduate roles, in Zambia or remote,
and to collaborations. I graduate in November 2027.

📍 Lusaka, Zambia · ✉️ wizachaila@gmail.com
