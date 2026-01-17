# FindBeam ⚡

A Privacy-First Online Tools Hub

FindBeam is a high-performance, privacy-focused collection of browser-based tools built with **pure HTML, CSS, and Vanilla JavaScript**, designed to run entirely on the client side.

The platform is optimized for **speed, SEO, scalability, and zero data collection**, hosted on **Cloudflare Pages** and enhanced with **Cloudflare Workers** where necessary.

🌐 Live site: https://findbeam.com

---

## 🚀 Core Principles

- ⚡ Ultra-fast (static + edge delivery)
- 🔐 Privacy-first (no user data stored)
- 📈 SEO-optimized (clean URLs, schema, sitemaps)
- 🧠 Client-side computation
- 💸 $0 infrastructure cost (Cloudflare free tier)
- 🔁 Highly reusable structure for 100+ tools

---

## 🧰 Available Tools (Growing)

- BMI Calculator (Adult)
- Child BMI & Percentile Calculator
- Base64 Encoder / Decoder
- CSS Minifier
- JavaScript Minifier
- HTML Minifier
- Hash Generators (MD5, SHA-256, SHA-512)
- IP Lookup
- Word Counter
- Password Generator
- Lorem Ipsum Generator
- Speed Test Tools

Each tool is accessible via clean URLs like:

``` Use in your Markdown file.
/bmi-calculator/
/bmi-calculator-child/
/base64-encode/
/css-minifier/
```
No query strings. No dynamic routing. No framework lock-in.

---

## 📁 Project Structure

```
/
├── index.html
├── about/
│   └── index.html
├── privacy/
│   └── index.html
├── terms/
│   └── index.html
├── bmi-calculator/
│   └── index.html
├── bmi-calculator-child/
│   └── index.html
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── js/
│   │   └── common.js
│   └── images/
├── robots.txt
├── sitemap.xml
├── llms.txt
└── 404.html

```
✅ Each folder maps directly to a public URL
✅ No /public, /dist, or /build in URLs

---

## 🧱 Technology Stack

- Hosting: Cloudflare Pages
- Edge APIs: Cloudflare Workers (ratings, lightweight APIs)
- Styling: Tailwind CSS (CDN or prebuilt CSS)
- Analytics: Umami (cookie-less, privacy-friendly)
- Consent: Minimal / lightweight consent banner (optional)
- SEO: Manual metadata + sitemap.xml
- Version Control: GitHub

No Node.js required.
No npm commands required.
No backend server required.

---

## 🔒 Privacy & Data Policy

No personal data collection

No health data stored or transmitted

No cookies for analytics

No Google Analytics

No Google Tag Manager

No fingerprinting

All calculations happen inside the user’s browser.

Designed to comply with:

GDPR (EU)

CCPA (California)

Global privacy-first standards

⚡ Performance Philosophy

Static HTML = instant load

Shared CSS & JS across tools

Zero server-side rendering

Cloudflare global edge caching

Minimal JavaScript execution

This architecture easily supports:

100+ tools

High traffic spikes

$0 hosting cost (Cloudflare Free tier)

🔁 Reusability Strategy

To avoid duplication (WordPress-style thinking, without WordPress):

Shared CSS → /assets/css/main.css

Shared JS → /assets/js/common.js

Reusable header/footer copied across pages

Same layout system across all tools

Future-ready upgrades:

Cloudflare Workers HTML injection

Build-time partials (optional later)

📊 Analytics (Recommended)

FindBeam uses Umami Analytics instead of GA/GTM:

Lightweight

Open-source

Cookie-less

GDPR compliant

Free (self-hosted or free tiers)

Works perfectly with Cloudflare Pages

Tracks:

Page views

Tool popularity

Referrers

Device types

💰 Monetization (Future-Ready)

Optional monetization paths:

Contextual affiliate links (hosting, SaaS, dev tools)

Non-intrusive ads (privacy-friendly networks)

Sponsored tools (clearly labeled)

Premium API endpoints (optional)

No dark UX. No tracking abuse.

🚀 Deployment Workflow

Code lives in GitHub

Cloudflare Pages connects to the repo

Every git push auto-deploys

Custom domain → findbeam.com

HTTPS, CDN & caching handled automatically

🛡️ Security

No backend database

No authentication surface

Cloudflare edge protection

Optional Cloudflare Turnstile for abuse prevention

Minimal third-party scripts

📜 License

This project is licensed under the MIT License.

You are free to:

Use

Modify

Distribute

Commercialize

With attribution.

❤️ Credits

Built with care in Dhaka, Bangladesh 🇧🇩
Powered by open web standards and Cloudflare’s global edge network.
