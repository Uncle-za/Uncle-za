# Hi, I'm Wiza 👋

**I care more about the engine than the paint job.**

With cars, that means turbos, superchargers, and why one engine pulls harder than another.
With software, it's the same question: what is actually happening underneath? How does a
database keep two companies' data apart? What happens when a request is retried halfway
through? Why does a system that works for ten users fall over at ten thousand?

I'm a Computer Science student at ZCAS University in Lusaka, working toward backend
engineering and large-scale systems.

## What I'm building

### ZAMHRMS — HR and payroll for Zambian businesses

A multi-tenant platform for employee records, attendance, leave, recruitment and payroll.
The source is private because it is a commercial product; the
**[case study](https://github.com/Uncle-za/zamhrms)** covers the architecture, the
decisions behind it, and a build log.

- Tenant isolation enforced by PostgreSQL row-level security, tested against a second tenant's data
- Payroll computes PAYE, NAPSA and NHIMA from versioned statutory rate tables, not hard-coded numbers
- Retried requests can't double-apply, thanks to database-backed idempotency keys
- 870+ automated tests, with linting, type checks, secret scanning and dependency audits on every pull request

`Django` · `PostgreSQL` · `Next.js` · `TypeScript` · `Docker` · `GitHub Actions`

## What I work with

- **Backend:** Python, Django, Django REST Framework, REST API design, OpenAPI
- **Databases:** PostgreSQL — row-level security, triggers, schema migrations in plain SQL
- **Frontend:** TypeScript, Next.js, React
- **Infrastructure:** Docker, GitHub Actions, Linux, Render
- **Also:** Flutter/Dart, VBA for Access and Excel

## What I'm taking apart next

Networking and distributed systems: how services stay correct when the network, a disk,
or another service fails. Projects from that work will appear here.

## Get in touch

Open to backend and infrastructure internships and graduate roles (in Zambia or remote),
and to collaborations. I graduate in November 2027.

📍 Lusaka, Zambia · ✉️ wizachaila@gmail.com
