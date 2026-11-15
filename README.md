# Awesome-Online-Discussion-Forum-Knowledge-Sharing

# Awesome Online Discussion Forum & Knowledge Sharing

> A curated list of top Online Discussion Forum and Knowledge Sharing platforms — both SaaS/Hosted commercial solutions and open-source alternatives for building communities, Q&A sites, and knowledge bases.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [Open-Source Software](#-open-source-software)
  - [Discourse](#discourse)
  - [Apache Answer](#apache-answer)
  - [Flarum](#flarum)
  - [NodeBB](#nodebb)
  - [phpBB](#phpbb)
  - [vBulletin](#vbulletin)
  - [Simple Machines Forum](#simple-machines-forum)
  - [MyBB](#mybb)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌐 Sector Overview & Market Dynamics

The global online community and discussion forum software market is valued at approximately **$2.5B–$4.5B** and is projected to expand beyond **$8B–$10B+** over the next decade at a CAGR of 12%–13.5%. The market is **moderately fragmented**: enterprise CRM suites (e.g., Salesforce, Khoros) consolidate large-scale enterprise customer communities, while mid-market platforms, creator communities, and open-source self-hosted solutions (e.g., Discourse, phpBB) maintain a substantial and diverse long-tail share.

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Online Discussion Forum and Knowledge Sharing platforms. Sorted descending by company scale (revenue / valuation):

| Product | Company Valuation / Revenue | Starting Pricing | Free Tier / Trial Limit | Key Focus & Features |
|:---|:---|:---|:---|:---|
| **Zoho Discussions (Zoho Community / Connect)** | **$12.5B valuation** (est.) / **~$1.5B annual revenue** (FY25, ₹12,313 Cr) | **$14/agent/month** (Zoho Desk Standard, billed annually, unlocks community forums) / **$1/user/month** (Zoho Connect internal) | **Free tier available forever**: Free for up to 5 users, 3 groups, and 3 custom apps/boards (Zoho Connect) / 3 agents (Zoho Desk, basic) | Part of the Zoho ecosystem; rich text editor, SEO, SSO integration, spam filtering, and migration from vBulletin/phpBB. |
| **Khoros Communities** | **$1B–$1.5B valuation** (Vista Equity buyout) / **~$250M–$285M annual revenue** | **$4,166/month** (contracts typically start at **$50,000/year**) | **No free tier; no public free trial** (Evaluation strictly via scheduled enterprise sales demo) | Enterprise-grade digital customer community, social media management, and care platform for Fortune 500 brands. |
| **Vanilla Forums (Higher Logic Vanilla)** | **$185M+ total capital raised** / **~$80M+ recurring revenue** (Higher Logic parent) | **$599/month** (Standard package; annualized contracts start at **$24,000/year**) | **No free tier; no self-serve free trial** (Available through scheduled sales demo and trial upon approval) | Enterprise customer community and knowledge base software with Q&A, gamification, and deep CRM/SSO integrations. |
| **Bettermode** | **$7.5M Seed funding** (backed by Bessemer & CRV) / **~$3.1M ARR** | **$149/month** (Starter tier billed annually, up to 10,000 members) | **14-day free trial** with full Starter/Growth features (no credit card required); no forever-free tier | Modern community platform featuring discussion forums, Q&A, AI spam filtering, federated search, and modular integrations. |

---

## 🟩 Open-Source Software

Self-hosted, community-driven Online Discussion Forum and Knowledge Sharing tools. The open-source ecosystem spans **modern community platforms**, **Apache-governed Q&A systems**, **lightweight modern forums**, and **long-standing PHP forums**.

### Discourse
**Stack:** Ruby on Rails / PostgreSQL / Redis | **License:** GPL
Discourse is the leading modern open-source forum platform, designed for **durable, searchable discussion** rather than ephemeral chat . It organizes posts into topics and categories, with real-time side-by-side preview, full WYSIWYG editing, OAuth2 and custom SSO support, and full export/portability [citation:10]. It is the open-source reference point for communities that outgrow simple group chat, and is frequently compared alongside Flarum and NodeBB. It requires a standard Ruby on Rails deployment stack with PostgreSQL and Redis.
**Best for:** Organizations wanting a proven, feature-rich community platform with strong moderation tools and a mature ecosystem, accepting the Rails deployment overhead.

### Apache Answer
**Stack:** Go / React / Docker | **License:** Apache-2.0
Apache Answer is an Apache-governed **Q&A platform software** for teams of any scale, suitable for community forums, help centers, or knowledge management platforms [citation:4]. It runs via a single Docker command (`docker run -d -p 9080:80 -v answer-data:/data --name answer apache/answer:1.4.5`) and provides a plugin system for extending features . It is positioned as a lightweight, Apache-licensed alternative to proprietary Q&A platforms like AnswerHub, with no licensing restrictions.
**Best for:** Teams wanting a straightforward, Apache-licensed Q&A platform with Docker deployment and plugin extensibility, particularly those in the Apache ecosystem.

### Flarum
**Stack:** PHP / MySQL | **License:** MIT
Flarum is a modern, lightweight open-source forum platform known for its clean design and fast performance. It is positioned as a simpler, more modern alternative to legacy forums like phpBB and vBulletin, with an extension ecosystem for adding features. It is not listed in the Wikipedia comparison table with the same level of detail as other platforms, but it is widely adopted among modern community builders .
**Best for:** Small to mid-sized communities wanting a modern, fast forum with a clean interface, accepting a smaller feature set than Discourse.

### NodeBB
**Stack:** Node.js / Redis / MongoDB | **License:** GPL-3.0
NodeBB is a Node.js-based forum platform designed for real-time discussions, with WebSocket support for live updates. It is positioned for communities wanting a modern, real-time experience with a Node.js stack. It is commonly compared alongside Discourse and Flarum as a modern open-source forum option.
**Best for:** Node.js-centric teams wanting a real-time forum with WebSocket support, accepting the Node.js/Redis/MongoDB stack.

### phpBB
**Stack:** PHP / MySQL/MariaDB/PostgreSQL/SQLite | **License:** GPL
phpBB is the most widely deployed open-source forum platform, with a long history and massive community. It provides flat forums, user-selectable themes, WYSIWYG editor, LDAP and OAuth SSO, and full export/portability [citation:10]. It is the benchmark for traditional forum software, with an extensive extension and style ecosystem. **Trade-off:** The interface feels dated compared to modern platforms like Discourse and Flarum, and performance can degrade at scale without optimization.
**Best for:** Communities wanting a proven, battle-tested forum with a massive ecosystem and low hosting requirements, accepting a dated UI.

### vBulletin
**Stack:** PHP / MySQL/MariaDB | **License:** Proprietary
vBulletin is a long-standing proprietary forum platform, with the latest release (6.2.0) in March 2026 [citation:10]. It is positioned for large communities willing to pay for a commercial license, with features including threaded discussions, user-selectable themes, and SSO support. **Trade-off:** It is proprietary, unlike the other platforms in this section, and its market position has declined against modern alternatives.
**Best for:** Organizations wanting a commercial forum platform with a long track record, accepting the proprietary licensing model.

### Simple Machines Forum
**Stack:** PHP / MySQL/MariaDB/PostgreSQL | **License:** BSD
Simple Machines Forum (SMF) is a free, professional-grade forum package for setting up online communities, with the latest release (2.1.8) in October 2026 [citation:10]. It provides flat forums, threaded discussions, WYSIWYG editor, and SSO support [citation:10]. It is positioned as a straightforward, BSD-licensed alternative to phpBB and vBulletin.
**Best for:** Communities wanting a permissive BSD-licensed forum with active maintenance, accepting a smaller ecosystem than phpBB.

### MyBB
**Stack:** PHP / MySQL | **License:** LGPL
MyBB is a free, open-source forum platform with a focus on ease of use and extensibility. It provides flat and threaded discussions, user-selectable themes, WYSIWYG editor, and SSO support [citation:10]. It is positioned for communities wanting a straightforward forum with a gentler learning curve than phpBB.
**Best for:** Communities wanting an accessible, LGPL-licensed forum with a straightforward setup, accepting a smaller ecosystem than the largest platforms.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Q&A Support | SSO | Self-Hosted | Best For |
|----------|---------|-------|-------------|-----|-------------|----------|
| **Zoho Discussions** | Proprietary | Cloud | (Forum) | ✅ | ❌ | Zoho ecosystem integration |
| **Bettermode** | Proprietary | Cloud | ✅ | ✅ | ❌ | Modern community + AI |
| **Vanilla Forums** | Proprietary | Cloud | ✅ | ✅ | ❌ | Enterprise community |
| **Discourse** | GPL | Ruby/Rails | ✅ | ✅ OAuth2 | ✅ | Proven modern community |
| **Apache Answer** | Apache-2.0 | Go/React/Docker | ✅ Q&A-focused | (Check) | ✅ | Apache-licensed Q&A |
| **Flarum** | MIT | PHP/MySQL | (Forum) | (Extensions) | ✅ | Lightweight modern forum |
| **NodeBB** | GPL-3.0 | Node.js | (Forum) | (Check) | ✅ | Real-time Node.js forum |
| **phpBB** | GPL | PHP/DB | (Forum) | ✅ LDAP/OAuth | ✅ | Proven legacy forum |
| **vBulletin** | Proprietary | PHP/MySQL | (Forum) | ✅ | ✅ | Commercial legacy forum |
| **SMF** | BSD | PHP/DB | (Forum) | ✅ | ✅ | Permissive BSD forum |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Online Discussion Forum or Knowledge Sharing tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The forum landscape splits between **modern community platforms** (Discourse, with the strongest feature set and ecosystem; Flarum and NodeBB offering lighter modern alternatives) and **Apache-governed Q&A systems** (Apache Answer, purpose-built for Q&A rather than general discussion). **Discourse** remains the dominant open-source choice for serious community building, with full SSO, real-time preview, and export portability [citation:10]. **Apache Answer** is the strongest choice for teams wanting a focused Q&A platform under a permissive Apache-2.0 license with simple Docker deployment [citation:4]. Legacy platforms like phpBB and SMF remain viable for communities that value stability and low hosting costs over modern UI, while vBulletin's proprietary model has lost ground to open-source alternatives.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
