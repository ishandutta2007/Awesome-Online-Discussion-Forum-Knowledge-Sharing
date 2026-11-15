# Awesome-Online-Discussion-Forum-Knowledge-Sharing

# Awesome Online Discussion Forum & Knowledge Sharing

> A curated list of top Online Discussion Forum and Knowledge Sharing platforms — both SaaS/Hosted commercial solutions and open-source alternatives for building communities, Q&A sites, and knowledge bases.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Zoho Discussions](#zoho-discussions)
  - [Bettermode](#bettermode)
  - [Vanilla Forums](#vanilla-forums)
  - [Khoros](#khoros)
- [Open-Source Software](#-open-source-software)
  - [Discourse](#discourse)
  - [Apache Answer](#apache-answer)
  - [Flarum](#flarum)
  - [NodeBB](#nodebb)
  - [phpBB](#phpbb)
  - [vBulletin](#vbulletin)
  - [Simple Machines Forum](#simple-machines-forum)
  - [MyBB](#mybb)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Online Discussion Forum and Knowledge Sharing platforms. These are not open-source but are included as reference points for feature comparison.

### Zoho Discussions
**Type:** Online forum software within the Zoho ecosystem
Zoho Discussions is an online forum software that helps create external and internal communication for problem-solving, topic discussion, and idea exchange . It offers a rich text editor, advanced search, SEO options, and extensive rebranding tools to align the community with your brand identity . It supports SSO integration to preserve existing login mechanisms and migration from vBulletin, phpBB, and Google Groups . The platform includes a built-in anti-spam engine and multi-language support (14+ languages). **Note:** The Chrome Web Store listing shows the extension was last updated in 2014, so verify current feature development status . Zoho Connect pricing starts at ¥7/user/month for the Enterprise plan (25-user minimum) and ¥21/user/month for the Flagship plan, with a free plan for up to 25 users [citation:5].
**Best for:** Organizations already using Zoho products wanting integrated forum capabilities with SSO and migration support.

### Bettermode
**Type:** Modern community platform with AI and extensive integrations
Bettermode is a modern community platform positioned for marketing and customer success teams to drive engagement, retention, and revenue . It offers discussion forums, Q&A, knowledge base capabilities, gamification, a drag-and-drop layout editor, analytics, and moderation tools [citation:7]. The platform is SOC 2 Type II compliant, supports GDPR and CCPA, and offers US/EU data residency . It includes AI spam detection, federated search, MCP (AI connector), and integrations with Salesforce, HubSpot, Intercom, Segment, and others [citation:6]. Pricing starts at **$149/month** [citation:7].
**Best for:** Mid-market to enterprise organizations wanting a polished, modern community platform with strong integrations and AI features.

### Vanilla Forums
**Type:** Enterprise community platform with knowledge base
Vanilla Forums provides discussion forums, Q&A, knowledge base, gamification, drag-and-drop layout editor, analytics, and moderation tools . The Enterprise tier adds SSO, advanced security, custom integrations, AI-powered features, dedicated support, and SLA agreements [citation:7]. **Pricing:** Vanilla uses custom pricing; third-party estimates place the Standard plan at **$599/month** for up to 1,000 users, with implementation costs of $2,000–$10,000 and potential hidden fees for customization and training [citation:13]. The Professional plan is estimated at $1,499/month [citation:13]. **No free plan is available**; prospective users must go through an enterprise sales process [citation:7].
**Best for:** Established organizations with complex community needs and a substantial budget, accepting the enterprise sales process.

### Khoros
**Type:** Enterprise community and social media management platform
Khoros provides enterprise-grade community forums, social media management, and care capabilities. It is positioned for large brands managing customer communities at scale, with pricing that reflects its enterprise focus.

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
