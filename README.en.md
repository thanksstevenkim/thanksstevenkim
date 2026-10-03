# Hi, I'm Steven Kim 👋

[Profile summary](./README.md) · [한국어 상세](./README.ko.md)

**Systems & Infrastructure · Technical Support · Service Operations**

I build, operate, troubleshoot, and document systems that people actually use.

My work is centered around **Linux infrastructure, production service operations, incident investigation, automation, and technical documentation**. Rather than collecting technologies for their own sake, I prefer learning through real systems: running services, investigating failures, improving repeatable processes, and documenting what happened.

I also work across **Korean, Japanese, and English** environments.

## What I work on

**Operate**  
Run and maintain self-hosted services, including a public Mastodon instance operated since 2022.

**Troubleshoot**  
Investigate production incidents across web servers, databases, application upgrades, search infrastructure, CI, and service integrations.

**Automate**  
Use Python and GitHub Actions to automate data collection, validation, filtering, health checks, and deployment workflows.

**Document**  
Turn incidents and experiments into runbooks, case studies, troubleshooting notes, and reusable knowledge.

---

## Featured Projects

### 🛠 [Mastodon Operations Lab](https://github.com/thanksstevenkim/mastodon-lab)

**Production service operations · Linux · Docker · Nginx · PostgreSQL · Cloudflare**

Operational knowledge collected from maintaining a self-hosted Mastodon service since 2022.

The repository focuses on real incidents and repeatable operations rather than a generic installation guide.

- Cloudflare 521 investigation after an upgrade
- incomplete database migrations
- Elasticsearch configuration issues
- CI failures caused by fork drift
- signup abuse and moderation tooling
- upgrade, backup, recovery, and maintenance runbooks

---

### 🧪 [LibreWiki Homelab](https://github.com/thanksstevenkim/librewiki-homelab)

**Linux · Nginx · PHP-FPM · MariaDB · MediaWiki · Migration**

A homelab built to reproduce and study an existing MediaWiki environment without affecting the original service.

It combines infrastructure practice with compatibility and migration work, including:

- Ubuntu Server deployment in a VM
- Nginx, PHP-FPM, and MariaDB configuration
- database backup and restoration
- MediaWiki page and revision migration
- extension and template dependency troubleshooting
- adapting older wiki customizations to newer MediaWiki markup

The project is gradually expanding toward network segmentation, monitoring, and disaster recovery practice.

---

### 🌐 [The Hitchhiker's Guide to the Fediverse](https://github.com/thanksstevenkim/the-hitchhikers-guide-to-the-fediverse)

**Python · Data pipelines · Validation · GitHub Actions · ActivityPub**

A Fediverse instance discovery and monitoring project backed by automatically collected public data.

The project includes:

- Python-based statistics collection
- canonical host and alias handling
- health-state transitions and failure thresholds
- spam and anomaly filtering
- software taxonomy and review queues
- automated validation
- scheduled GitHub Actions workflows
- static deployment through GitHub Pages

It is also an experiment in dealing with incomplete, changing, and sometimes unreliable distributed-system data.

---

### 📚 [thanks-wiki](https://github.com/thanksstevenkim/thanks-wiki)

**Knowledge engineering · Astro · Documentation · Case studies**

A personal knowledge base for turning observations, technical incidents, and research conversations into reusable knowledge.

The structure separates:

- **Notes** — observations, hypotheses, cases, and the origins of ideas
- **Docs** — reusable methods that emerge from multiple notes and cases

Rather than preserving conclusions alone, the project keeps the concrete examples and reasoning needed to reconstruct why an idea emerged.

---

## How I approach technical work

I am most interested in what happens **after a system is deployed**.

When something fails, I try to preserve more than the final command that fixed it:

```text
symptom
  ↓
evidence
  ↓
hypotheses
  ↓
root cause
  ↓
change
  ↓
verification
  ↓
reusable procedure
```

The goal is not only to restore the service, but to make the next investigation easier.

## Selected Experience

```text
Systems & Operations
├── Linux server administration
├── Docker-based services
├── Nginx / Cloudflare
├── PostgreSQL / MariaDB / Redis
├── backup and recovery
└── incident response

Automation
├── Python
├── GitHub Actions
├── data validation
├── health monitoring logic
└── repeatable operational workflows

Documentation
├── incident reports
├── runbooks
├── troubleshooting notes
├── architecture documentation
└── knowledge bases
```

## Languages

- 🇰🇷 Korean — Native
- 🇯🇵 Japanese — Professional working proficiency
- 🇬🇧 English — Professional working proficiency

## Portfolio

For a more structured overview of my projects and experience:

**[thanksstevenkim.dev](https://thanksstevenkim.dev)**
