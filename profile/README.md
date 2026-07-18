# ExamManager

**Exam coordination and timed exam delivery for educators.**

ExamManager is a portfolio of apps built around exam timers, exam dashboards, and classroom coordination — from an early Vue timer through Next.js SaaS iterations.

[dan@x70.one](mailto:dan@x70.one)

---

## Repositories

| Repository | Role |
| --- | --- |
| [exams-landing](https://github.com/ExamManager/exams-landing) | Waitlist / marketing landing page |
| [exams-app-v1](https://github.com/ExamManager/exams-app-v1) | Vue 3 exam timer (frontend + Express) |
| [exams-app-v2](https://github.com/ExamManager/exams-app-v2) | Next.js + Prisma exam manager |
| [exams-app-v3](https://github.com/ExamManager/exams-app-v3) | T3 / Drizzle SaaS rewrite (orgs, billing, docs) |

## Stack

- **Apps:** Next.js, Vue 3, React, TypeScript, Tailwind CSS
- **Auth & data:** NextAuth, Prisma, Drizzle, Supabase, Postgres / MySQL
- **Billing & email:** Stripe, Resend
- **Tooling:** Yarn, Vite, Contentlayer

## Evolution

```text
v1 (Vue timer) ──► v2 (Prisma / Taxonomy-era) ──► v3 (T3 / Drizzle SaaS)
                         │
landing (waitlist) ──────┘
```

## Note

These repos are maintained as an open portfolio of the ExamManager product line. Prefer **exams-app-v3** for the latest architecture direction.
