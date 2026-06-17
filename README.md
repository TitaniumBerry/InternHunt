# InternHunt

A founder-focused internship platform that helps students discover opportunities, craft personalized cold emails, and access battle-tested outreach resources that have led to real internship offers.

![Cloudflare Workers](https://img.shields.io/badge/cloudflare-workers-orange)
![Cloudflare Pages](https://img.shields.io/badge/cloudflare-pages-orange)
![JavaScript](https://img.shields.io/badge/javascript-es6-yellow)
![HTML5](https://img.shields.io/badge/html5-frontend-red)
![CSS3](https://img.shields.io/badge/css3-responsive-blue)

---

## Live Demo

[https://internhunt.pages.dev](https://internhunt-1yo.pages.dev/)

---

## What it does

InternHunt provides students with a curated collection of internship-hunting resources built around one principle:

**Founders hire initiative.**

The platform includes proven cold-email frameworks, resume guidance, founder outreach strategies, interview preparation resources, and an AI-powered cold email generator that helps students craft personalized outreach messages at scale.

The project originated from internship-hunting systems developed and tested by Rajay Vardhan Rai, whose templates and strategies led to multiple internship offers and founder responses. The platform transforms those resources into a structured and accessible web experience.

---

## Features

* **AI Cold Email Generator** — generate personalized founder outreach emails
* **Founder Outreach Playbook** — proven cold-email templates and frameworks
* **Internship Resource Hub** — curated guides, tools, and preparation material
* **Responsive UI** — optimized for desktop and mobile devices
* **Interactive Resource Navigation** — organized learning paths for students
* **Image Lightbox Viewer** — enlarge and inspect outreach examples
* **Cloudflare Worker Backend** — serverless API handling AI requests
* **Fast Global Delivery** — deployed through Cloudflare's edge network
* **Zero-Cost Hosting** — fully deployable on free Cloudflare services

---

## Tech Stack

| Layer      | Technology                      |
| ---------- | ------------------------------- |
| Frontend   | HTML5, CSS3, Vanilla JavaScript |
| Backend    | Cloudflare Workers              |
| Hosting    | Cloudflare Pages                |
| API Layer  | Serverless Edge Functions       |
| Deployment | GitHub + Cloudflare             |
| Styling    | Custom CSS                      |

---

## Local Setup

### Requirements

* Node.js 18+
* npm
* Cloudflare account (for deployment)

### Clone Repository

```bash
git clone https://github.com/TitaniumBerry/InternHunt.git
cd InternHunt
```

### Frontend Development

If using a static frontend:

```bash
python -m http.server 8000
```

or

```bash
npx serve .
```

Visit:

```text
http://localhost:8000
```

### Backend Development

Install dependencies:

```bash
npm install
```

Run Cloudflare Worker locally:

```bash
npx wrangler dev
```

The worker will be available locally for testing and API development.

---

## Deployment

### Frontend

Deploy using Cloudflare Pages:

1. Push repository to GitHub
2. Create a Cloudflare Pages project
3. Connect GitHub repository
4. Deploy automatically

### Backend

Deploy Cloudflare Worker:

```bash
npx wrangler deploy
```

Cloudflare automatically provisions a public endpoint and global edge deployment.

---

## Project Structure

```text
InternHunt/
├── index.html             # Main application page
├── styles.css             # Application styling
├── image-modal.js         # Image lightbox functionality
├── worker.js              # Backend worker source code(gitignored)
├── assets/
│   ├── coldmail1.jpeg
│   ├── coldmail2.jpeg
│   └── coldmail3.jpeg
└── README.md
```

---

## Core Workflow

```text
Student Input
      │
      ▼
Cold Email Generator
      │
      ▼
Cloudflare Worker API
      │
      ▼
Generated Founder Outreach
      │
      ▼
Applications & Responses
```

---

## Contributors

### Rajay Vardhan Rai

2024A2PS1255P · BITS Pilani, Pilani Campus

Created the original internship outreach framework, cold-email templates, resource collection, and founder-focused internship strategy that powers InternHunt.

### Chirag Bajaj

2025B5PS1320P · BITS Pilani, Pilani Campus

Built the backend infrastructure, deployment pipeline, platform integration, UI improvements, hosting architecture, and technical systems powering InternHunt.

---

## Notes

InternHunt was built to reduce the information gap faced by students searching for internships. Instead of relying on placement portals, referrals, or paid services, the platform focuses on direct founder outreach, initiative-driven applications, and practical resources that have been tested in real internship searches.

The project combines proven outreach strategies with modern serverless infrastructure to create a fast, accessible platform for students across disciplines.
