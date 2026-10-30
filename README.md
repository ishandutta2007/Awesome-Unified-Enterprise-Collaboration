# Awesome Unified Enterprise Collaboration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of leading enterprise collaboration platforms, unified workplace communication suites, and self-hosted open-source alternatives.

**Focused on Team Chat, Video Conferencing, Work Management & Self-Hosted Digital Workspaces.**

Last updated: October 2026

---

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
  - [Open-Source Projects Ranked by Community Adoption](#open-source-projects-ranked-by-community-adoption)
  - [Architectural Categories & Functional Stacks](#architectural-categories--functional-stacks)
- [Self-Hosting vs. Unified SaaS Trade-offs](#self-hosting-vs-unified-saas-trade-offs)
- [How to Contribute](#how-to-contribute)
- [License & Disclaimer](#license--disclaimer)

---

## Sector Overview & Market Dynamics

The global enterprise collaboration market is estimated at **$60B–$73B in 2025–2026**, projected to exceed **$135B–$160B by the early 2030s** at an 11–13% CAGR driven by generative AI co-pilots, hybrid workforce persistence, and vendor consolidation. The sector exhibits a **moderately concentrated, bifurcated structure**: tech giants (Microsoft and Google) dominate baseline productivity suites and identity layers with a near-duopoly, while specialized players (Salesforce/Slack, Zoom, Atlassian, Notion, and Monday.com) fiercely contest high-value workflows across messaging, async documentation, and agile work execution.

---

## SaaS & Hosted Platforms

The table below catalogs major commercial collaboration suites sorted in descending order by company scale (valuation or annual revenue).

| SaaS Product | Company Scale (Valuation / Revenue) | Starting Paid Tier Pricing | Free Tier / Trial Limits | Core Focus & Enterprise Positioning |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams)** | ~$3.1T Market Cap (Microsoft) | **$4.00** / user / month *(Teams Essentials, billed annually)* | **Free forever plan**: Capped at 60 minutes per group meeting, 100 participants per meeting, and 5 GB total cloud storage. No cloud recording or desktop Office apps included. | Integrated collaboration hub within Microsoft 365 combining chat, meetings, VoIP, and deep SharePoint/OneDrive integration. |
| **[Google Workspace](https://workspace.google.com/)** | ~$2.2T Market Cap (Alphabet) | **$7.00** / user / month *(Business Starter, billed annually)* | **14-day free trial**: Up to 10 user accounts with full suite access (Gmail, Meet, Drive, Docs, Chat), capped at 500 emails/day during trial. No permanent free tier. | Real-time cloud-native office and communications suite with integrated Gemini AI, Docs, Drive, and Meet. |
| **[Slack](https://slack.com/)** | ~$27.7B Acquisition / ~$330B Market Cap (Salesforce) | **$7.25** / user / month *(Pro plan, billed annually)* | **Free forever plan**: 90-day searchable message and file history visibility (older data archived/deleted after 1 year), 10 app integrations max, 1-on-1 audio/video huddles only, 5 GB total workspace storage. | The benchmark for channel-based team messaging, developer integrations, huddles, and workflow automation. |
| **[Cisco Webex](https://www.webex.com/)** | ~$220B Market Cap (Cisco Systems) | **$12.00** / user / month *(Webex Meet / Starter, billed annually)* | **Free forever plan**: 40-minute limit on group meetings (unlimited 1:1 calls), up to 100 attendees, local recording only, no cloud storage or advanced AI assistant. | Highly secure video meetings, messaging, VoIP calling, and room hardware deeply optimized for enterprise network architectures. |
| **[ByteDance (Lark)](https://www.larksuite.com/)** | ~$220B+ Valuation (ByteDance) | **$12.00** / user / month *(Pro plan, billed annually)* | **Free forever Starter plan**: Up to 20 users, 60 minutes per meeting (up to 100 participants), 100 GB shared organization cloud storage, and unlimited chat history. | All-in-one Asian-market powerhouse combining chat, collaborative docs, calendar, no-code Base workflows, and video meetings. |
| **[Atlassian One](https://www.atlassian.com/)** | ~$45B–$50B Market Cap (Atlassian) | **$8.48** / user / month *(Jira Standard, billed annually)*; **$5.42** / user / month *(Confluence Standard)* | **Free forever plan**: Up to 10 users per product site (Jira, Confluence), 2 GB total file storage, standard Scrum/Kanban boards, 50 automation runs/month, community support only. | Unified work platform uniting Jira (issue tracking), Confluence (wiki/knowledge management), and Loom (async video). |
| **[Zoom Workplace](https://www.zoom.com/)** | ~$22B Market Cap (Zoom Video Communications) | **$13.33–$14.16** / user / month *(Pro plan, billed annually at $159.90–$170/year)* | **Free forever Basic plan**: 40-minute limit per meeting (group and 1-on-1), up to 100 participants, local recording only (0 GB cloud storage), 3 active whiteboards, and 3 AI summary uses/month. | Video-first communications platform expanding into team chat, phone, whiteboarding, and workplace scheduling. |
| **[Notion](https://www.notion.com/)** | ~$10B–$11B Private Valuation (Notion Labs) | **$10.00** / member / month *(Plus plan, billed annually)* | **Free forever plan**: Unlimited pages and blocks for solo users, 1,000 blocks limit for shared team workspaces (2+ members), 5 MB max file upload size, 7-day page history, and 10 guest collaborators. | Flexible all-in-one workspace blending modular docs, relational databases, wikis, project boards, and AI search. |
| **[Monday.com](https://monday.com/)** | ~$13B–$15B Market Cap (Monday.com Ltd) | **$9.00** / seat / month *(Basic plan, billed annually, minimum 3 seats = $27/mo)* | **Free forever plan**: Strictly capped at 2 seats, up to 3 boards total, 200 items/tasks maximum across account, 500 MB storage, and zero automations/integrations. | Customizable Work OS featuring flexible tables, visual dashboards, task pipelines, and automated business workflows. |
| **[Asana](https://asana.com/)** | ~$3B–$4B Market Cap (Asana Inc.) | **$10.99** / user / month *(Starter plan, billed annually, 2-seat minimum)* | **Free forever Personal plan**: Strictly capped at 2 users, unlimited tasks/projects, 100 MB max per file attachment, list/board/calendar views only, zero workflow automations, custom fields, or timeline/Gantt charts. | Work management suite centered on enterprise portfolio management, goals (OKRs), project tracking, and cross-functional coordination. |

---

## Open-Source GitHub Projects

Open-source unified collaboration software offers organizations total data sovereignty, zero per-seat licensing bloat, and GDPR/HIPAA-compliant on-premises deployments.

### Open-Source Projects Ranked by Community Adoption

Repos are ordered below in descending order by GitHub stargazers. Each badge reflects real-time stars and links directly to that repository's stargazers community.

| Rank | Project | GitHub Community | License | Primary Architectural Niche | Key Differentiators |
| :---: | :--- | :---: | :---: | :--- | :--- |
| 1 | **[AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)** | [![GitHub stars](https://img.shields.io/github/stars/AppFlowy-IO/AppFlowy?style=social&color=white)](https://github.com/AppFlowy-IO/AppFlowy/stargazers) | AGPL-3.0 | Notion Alternative / Local-First Docs | Flutter and Rust-powered privacy-first workspace. True local data control with self-hosted cloud sync and AI plugins. |
| 2 | **[AFFiNE](https://github.com/toeverything/AFFiNE)** | [![GitHub stars](https://img.shields.io/github/stars/toeverything/AFFiNE?style=social&color=white)](https://github.com/toeverything/AFFiNE/stargazers) | MIT | All-in-One Canvas / Notion + Miro Alternative | Merges structured text documents, mind maps, and infinite whiteboards into a single canvas with local-first CRDT sync. |
| 3 | **[Plane](https://github.com/makeplane/plane)** | [![GitHub stars](https://img.shields.io/github/stars/makeplane/plane?style=social&color=white)](https://github.com/makeplane/plane/stargazers) | AGPL-3.0 | Jira / Linear / Asana Alternative | Modern software project management featuring issues, cycles, modules, roadmaps, analytical analytics, and rich markdown docs. |
| 4 | **[Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)** | [![GitHub stars](https://img.shields.io/github/stars/RocketChat/Rocket.Chat?style=social&color=white)](https://github.com/RocketChat/Rocket.Chat/stargazers) | MIT | Slack / Omnichannel Chat Alternative | Enterprise-grade messaging platform with team chat, omnichannel customer support inbox, Matrix federation, VoIP, and E2E encryption. |
| 5 | **[Mattermost](https://github.com/mattermost/mattermost)** | [![GitHub stars](https://img.shields.io/github/stars/mattermost/mattermost?style=social&color=white)](https://github.com/mattermost/mattermost/stargazers) | Apache-2.0 / Commercial | Secure Dev & Ops Chat Platform | High-security collaboration suite built for technical teams in air-gapped or regulated sectors, combining chat, playbooks, and boards. |
| 6 | **[Nextcloud Hub](https://github.com/nextcloud/server)** | [![GitHub stars](https://img.shields.io/github/stars/nextcloud/server?style=social&color=white)](https://github.com/nextcloud/server/stargazers) | AGPL-3.0 | Microsoft 365 / Google Workspace Alternative | The most complete self-hosted suite. Bundles Nextcloud Files, Talk (video/chat), Groupware (Mail/Calendar), Office, and Deck (Kanban). |
| 7 | **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)** | [![GitHub stars](https://img.shields.io/github/stars/jitsi/jitsi-meet?style=social&color=white)](https://github.com/jitsi/jitsi-meet/stargazers) | Apache-2.0 | Zoom / Google Meet Alternative | Production-tested WebRTC video conferencing with no account requirements, browser-first design, recording (Jibri), and SIP dial-in (Jigasi). |
| 8 | **[Huly Platform](https://github.com/hcengineering/platform)** | [![GitHub stars](https://img.shields.io/github/stars/hcengineering/platform?style=social&color=white)](https://github.com/hcengineering/platform/stargazers) | EPL-2.0 | All-in-One Workplace Suite | Unified "everything workspace" consolidating task management, team chat, audio virtual office rooms, and collaborative docs in one app. |
| 9 | **[Zulip](https://github.com/zulip/zulip)** | [![GitHub stars](https://img.shields.io/github/stars/zulip/zulip?style=social&color=white)](https://github.com/zulip/zulip/stargazers) | Apache-2.0 | Threaded Team Chat Platform | Unique topic-based threading model within streams that prevents notification overload and preserves contextual institutional memory. |
| 10 | **[LiveKit](https://github.com/livekit/livekit)** | [![GitHub stars](https://img.shields.io/github/stars/livekit/livekit?style=social&color=white)](https://github.com/livekit/livekit/stargazers) | Apache-2.0 | Real-time Video/Audio & WebRTC Infrastructure | Distributed WebRTC SFU server powering real-time video conferencing, spatial audio, and multimodal real-time AI agents. |
| 11 | **[Wekan](https://github.com/wekan/wekan)** | [![GitHub stars](https://img.shields.io/github/stars/wekan/wekan?style=social&color=white)](https://github.com/wekan/wekan/stargazers) | MIT | Trello / Kanban Board Alternative | Lightweight, responsive collaborative Kanban board supporting custom fields, swimlanes, subtasks, and international multi-language setups. |
| 12 | **[OpenProject](https://github.com/opf/openproject)** | [![GitHub stars](https://img.shields.io/github/stars/opf/openproject?style=social&color=white)](https://github.com/opf/openproject/stargazers) | GPL-3.0 | Jira / MS Project Alternative | Full-lifecycle project management with Gantt charts, sprint boards, bug tracking, time reporting, and bidirectional XWiki integration. |
| 13 | **[Element Web (Matrix)](https://github.com/element-hq/element-web)** | [![GitHub stars](https://img.shields.io/github/stars/element-hq/element-web?style=social&color=white)](https://github.com/element-hq/element-web/stargazers) | AGPL-3.0 | Secure Matrix Protocol Client | Standard web client for the federated Matrix protocol, featuring Olm/Megolm end-to-end encryption, multi-server spaces, and Slack/Teams bridges. |
| 14 | **[BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)** | [![GitHub stars](https://img.shields.io/github/stars/bigbluebutton/bigbluebutton?style=social&color=white)](https://github.com/bigbluebutton/bigbluebutton/stargazers) | LGPL-3.0 | Web Conferencing & Virtual Classrooms | Real-time presentation and conference system with breakout rooms, multi-user whiteboards, shared notes, and screen sharing. |
| 15 | **[CryptPad](https://github.com/cryptpad/cryptpad)** | [![GitHub stars](https://img.shields.io/github/stars/cryptpad/cryptpad?style=social&color=white)](https://github.com/cryptpad/cryptpad/stargazers) | AGPL-3.0 | Zero-Knowledge Document Suite | Privacy-by-design encrypted collaboration suite. Rich text docs, spreadsheets, code pads, and kanban boards encrypted client-side. |
| 16 | **[HedgeDoc](https://github.com/hedgedoc/hedgedoc)** | [![GitHub stars](https://img.shields.io/github/stars/hedgedoc/hedgedoc?style=social&color=white)](https://github.com/hedgedoc/hedgedoc/stargazers) | AGPL-3.0 | Collaborative Markdown Notes | Collaborative real-time markdown editor with live side-by-side rendering, MathJax, graph diagrams, and granular permission controls. |
| 17 | **[HumHub](https://github.com/humhub/humhub)** | [![GitHub stars](https://img.shields.io/github/stars/humhub/humhub?style=social&color=white)](https://github.com/humhub/humhub/stargazers) | AGPL-3.0 | Enterprise Social Network & Intranet | Modular social intranet platform featuring internal activity streams, group spaces, user directories, file sharing, and wikis. |
| 18 | **[Colanode](https://github.com/colanode/colanode)** | [![GitHub stars](https://img.shields.io/github/stars/colanode/colanode?style=social&color=white)](https://github.com/colanode/colanode/stargazers) | Apache-2.0 | Local-First Collaboration | Offline-first modular workspace combining team channels, rich-text documents, and relational databases. |
| 19 | **[Collabora Online](https://github.com/CollaboraOnline/online)** | [![GitHub stars](https://img.shields.io/github/stars/CollaboraOnline/online?style=social&color=white)](https://github.com/CollaboraOnline/online/stargazers) | MPL-2.0 | Online Office Engine (LibreOffice-based) | Cloud office document suite compatible with DOCX, XLSX, and PPTX; deeply integrates with Nextcloud and ownCloud for real-time co-authoring. |
| 20 | **[XWiki Platform](https://github.com/xwiki/xwiki-platform)** | [![GitHub stars](https://img.shields.io/github/stars/xwiki/xwiki-platform?style=social&color=white)](https://github.com/xwiki/xwiki-platform/stargazers) | LGPL-2.1 | Confluence / Enterprise Wiki Alternative | Extensible enterprise wiki platform with fine-grained rights, structured data apps, import/export migration tools, and OpenProject task pairing. |

---

### Architectural Categories & Functional Stacks

For architects mapping out specific replacements, open-source projects typically assemble across distinct layers:

1. **Full Workspace & Office Productivity Suites**: [Nextcloud Hub](https://github.com/nextcloud/server), [Collabora Online](https://github.com/CollaboraOnline/online), [CryptPad](https://github.com/cryptpad/cryptpad)
2. **Team Chat & Asynchronous Messaging**: [Rocket.Chat](https://github.com/RocketChat/Rocket.Chat), [Mattermost](https://github.com/mattermost/mattermost), [Zulip](https://github.com/zulip/zulip), [Element (Matrix)](https://github.com/element-hq/element-web)
3. **Audio & Video Conferencing**: [Jitsi Meet](https://github.com/jitsi/jitsi-meet), [BigBlueButton](https://github.com/bigbluebutton/bigbluebutton), [LiveKit](https://github.com/livekit/livekit)
4. **Task, Issue & Project Tracking (Atlassian Replacements)**: [Plane](https://github.com/makeplane/plane), [OpenProject](https://github.com/opf/openproject), [Wekan](https://github.com/wekan/wekan), [Huly](https://github.com/hcengineering/platform)
5. **Knowledge Management & Canvas Workspaces**: [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy), [AFFiNE](https://github.com/toeverything/AFFiNE), [XWiki](https://github.com/xwiki/xwiki-platform), [HedgeDoc](https://github.com/hedgedoc/hedgedoc)

---

## Self-Hosting vs. Unified SaaS Trade-offs

| Dimension | Hosted Enterprise SaaS (Teams / Workspace / Slack) | Self-Hosted Open-Source Stack (Nextcloud + Rocket.Chat + Jitsi) |
| :--- | :--- | :--- |
| **Integration Experience** | Seamless out-of-the-box turnkey experience; universal global search across files, chat, and calendars. | Component-level integration; requires deploying SSO (OIDC/SAML like Keycloak) and cross-app Webhooks. |
| **Data Sovereignty & Compliance** | Data stored in vendor cloud; subject to US CLOUD Act, tenant lock-in, and opaque AI scraping terms. | 100% data ownership; air-gapped deployment, custom encryption key management, and strict GDPR compliance. |
| **Operational Overhead** | Managed SLAs, zero maintenance, automatic backups, continuous feature deployments. | Sysadmin responsibility for scaling WebRTC media bridges, database backups, turn servers, and security patches. |
| **Total Cost of Ownership** | Predictable per-seat monthly subscription fee scaling directly with organization headcount. | Server infrastructure (compute/bandwidth) and engineering time, with zero incremental licensing fees. |

---

## How to Contribute

Contributions are welcome! Please follow these guidelines:

1. Fork this repository and create your branch (`git checkout -b feature/new-tool`).
2. Add or update entries matching the existing markdown formatting and factual standards.
3. Include links to official repositories or official websites.
4. Verify GitHub star badges and URLs before submitting.
5. Submit a descriptive Pull Request.

---

## License & Disclaimer

- Curated with care for IT directors, software architects, and DevOps engineers evaluating enterprise collaboration stacks.
- All product names, logos, and brands are property of their respective owners.
- Ensure compliance with applicable open-source licenses (AGPL-3.0, GPL-3.0, EPL-2.0, MPL-2.0, Apache-2.0, MIT) before commercial multi-tenant distribution or deployment.
