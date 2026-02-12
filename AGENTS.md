# Agents — Strategy Summary

## Target career outcome
- Become a web automation consultant and productize a workflow-automation offering for student / early-stage entrepreneurs (NJ/NY focus).
- Short-term (6–12 months): run 1–3 paid pilots, publish 2 case studies, convert pilots to revenue-share deals.
- Medium-term (12–24 months): productize core automation into a repeatable service offering and maintain 5–15 active clients under hybrid fees + revenue-share.

## Chosen tools and why
- **Portfolio & demos:** GitHub Pages — fastest way to publish `North-Star` portfolio and demo links from your GitHub repo.
- **Frontend (MVP):** Static SPA using plain HTML/CSS/JS now; upgrade to React/Vite when rebuilding for scale. Fast to iterate with your current skills.
- **Hosting / serverless:** Vercel or Netlify — simple CI/CD from GitHub, instant deploys, serverless functions for light backend logic.
- **Database / backend:** Airtable (no-code admin, fastest for pilots) or Supabase (auth + Postgres for scale). Start with Airtable to prove value quickly.
- **Automation / integrations:** Zapier or Make — connect intake forms, email, Google Calendar, form responses, and trigger workflows without heavy backend work.
- **Calendar & reminders:** Google Calendar API (or calendar sync via Zapier) for scheduling and reminders.
- **Payments:** Stripe — reliable, easy to integrate for setup fees and future subscription/revenue-share flows.

Why these choices: they minimize engineering time for pilots, allow rapid iteration, and use generous free tiers so you can validate product-market fit cheaply before investing in custom infra.

## Sitemap (MVP + growth)
- `/` — Landing page: one-sentence value prop, CTA to request a free pilot, NJ/NY SEO headline.
- `/solutions` — Workflow Automation: short feature list (intake → normalize → schedule → monitor).
- `/pilot` — Pilot signup + case study promise (free/discounted pilot for campus founders).
- `/pricing` — Setup fee + revenue-share model explained and example numbers.
- `/case-studies` — Pilot stories, metrics, screenshots, testimonials.
- `/about` — About you, NJIT background, GitHub link to `North-Star/README.md` and relevant repos.
- `/contact` — Contact form, Calendly or booking link.
- `/docs` — Onboarding & simple admin guide for clients.
- `/blog` — Short SEO posts aimed at NJ/NY small businesses and student entrepreneurs.

## Non-negotiables
- **Clear agreement:** All revenue-share pilots must have a short written agreement (scope, duration, share %, minimum floor).
- **Data privacy:** Client data must be handled securely; avoid storing sensitive payment data; prefer integrations (Stripe, Google) that handle PCI/PII.
- **Fast pilot cadence:** Ship pilots in 2–6 weeks to gather case-study evidence quickly.
- **Transparent reporting:** Track and share simple metrics (tasks automated, time saved, revenue attributed) with clients monthly.
- **SEO & local focus:** All public pages must include NJ/NY-targeted keywords and local signals (NJIT mention, location pages, Google My Business later).

## NJ / NY SEO-optimized keywords (use in titles, meta, H1s, and landing copy)
- Primary: "workflow automation NJ", "workflow automation New Jersey", "web automation NJ", "automation for small business NJ", "student entrepreneur web developer NJ".
- Secondary: "workflow automation NYC", "automation for startups NY", "web developer for startups NJ/NY", "NJIT web developer", "automation solutions New Jersey".
- Local long-tail examples: "automate booking for small business Newark NJ", "student startup automation NJIT", "affordable web automation for startups NYC".

Guidance: prioritize a single local focus per page (e.g., Landing → New Jersey, Blog posts → NYC-specific problems) and include structured data (JSON-LD) for local business when ready.

## Quick next steps
1. Publish this file to the repo and add a lightweight landing page on GitHub Pages with the core value proposition and the pilot signup form.
2. Recruit 1 pilot via NJIT channels and run the 6-week MVP timeline: intake form → Airtable schema → Zapier automations → calendar sync → demo.
3. Collect metrics and produce the first case study for `/case-studies`.

---
Created to capture our CTO strategy for the `North-Star` project and first commercial offering targeting NJ/NY student entrepreneurs.
