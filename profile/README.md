<h1 align="center">Elimu Bora Solutions</h1>

<p align="center">
  <strong>Software for Kenyan schools.</strong>
</p>

<p align="center">
  <a href="https://elimuboraerp.com">Website</a>
  ·
  <a href="https://elimuboraerp.com/blog">Blog</a>
  ·
  <a href="https://elimuboraerp.com/contact">Contact</a>
</p>

---

## Hello 👋

We are **Elimu Bora Solutions Co.**, a Nairobi-based software company. *Elimu Bora* is Swahili for *"quality education"*, and that is the standard we hold ourselves to when we build for the schools we serve.

Our work is focused on the Kenyan education market: private primary and secondary schools running on either CBC or the legacy 8-4-4 curriculum. Everything we ship is designed for that context first, not retrofitted from a generic global template.

## Our flagship product: Elimu Bora ERP

A multi-tenant school management platform that replaces paper registers, Excel cashbooks, and scattered WhatsApp groups with one unified system. Every school we onboard gets its own isolated database and subdomain.

What it covers:

- Student, guardian, teacher, and support staff records
- CBC and 8-4-4 curriculum structure, pathways, and subjects
- Academic years, terms, assessments, grading, and report cards
- Attendance registers with automatic guardian notifications and follow-up workflows
- Fee invoicing with native M-Pesa STK Push, student wallets, and automated receipts
- Inventory, procurement, purchase orders, and low-stock alerts
- Timetables, lessons, school events, sports, and clubs
- A tamper-proof activity log across every module

Curious? Read the full product story at [elimuboraerp.com](https://elimuboraerp.com) or browse the [blog](https://elimuboraerp.com/blog).

## How we build

We reach for boring, reliable technology on purpose. The platform is server-rendered, queue-driven, and easy to reason about long after it ships.

**Backend**
- PHP 8.4, Laravel 12
- Filament 4 for admin panels
- Livewire 3 and Alpine.js for reactive pages without a separate SPA
- Spatie packages for roles, activity logging, and PDF generation
- `stancl/tenancy` v3 for multi-database multi-tenancy

**Frontend**
- Astro 6 and Vue 3 for the marketing site
- Tailwind CSS 4 across the board

**Infrastructure**
- DigitalOcean, managed with Laravel Forge
- Cloudflare for DNS, CDN, and Turnstile
- DigitalOcean Spaces for file storage (one shared bucket, per-tenant prefixes)
- MySQL per-tenant databases, plus a central database for tenant metadata

**Integrations**
- Safaricom Daraja for M-Pesa STK Push and C2B
- Stripe (via Laravel Cashier) for platform subscriptions
- Zoho ZeptoMail for transactional email
- Zoho Campaigns for newsletters
- Africa's Talking for SMS
- PostHog for product analytics

## About these repositories

Most of our work lives in private repositories while the product is still growing up. What you find here are the smaller public pieces: tools, libraries, and open-source work we have found useful and want to share. Over time we expect more of our work to move out into the open.

## Working with us

If you are:

- **A school** evaluating the product, head to [elimuboraerp.com/contact](https://elimuboraerp.com/contact) and we will set up a demo.
- **A developer** curious about how we build, our [blog](https://elimuboraerp.com/blog) is the best window into our thinking.
- **A potential partner** (education NGO, county education office, training provider, or reseller), the contact form is the fastest way to reach us.

---

<p align="center">
  Built in Kenya, for schools across Kenya.
</p>
