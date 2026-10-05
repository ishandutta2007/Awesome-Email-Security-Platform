# Awesome-Email-Security-Platform

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.

Here is the complete, ready-to-paste README.md for **Awesome-Email-Security-Platform**.

---

# Awesome-Email-Security-Platform

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Phishing Protection, Business Email Compromise (BEC) Defense, Data Loss Prevention & Email Gateway Security*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Email Security**. These tools help organizations protect against phishing, malware, business email compromise (BEC), ransomware, and data exfiltration via email and cloud collaboration channels.

**Examples** include Microsoft Defender for Office 365, Proofpoint, Mimecast, Abnormal Security, Cisco Secure Email, Avanan (Check Point), Barracuda Email Protection, IRONSCALES, Perception Point, and Graphus (the category leaders).

**Open-source emphasis**: The open-source email security ecosystem is **focused on gateway filtering and DLP**. **Sagator** is a mature antivirus/anti-spam gateway for Postfix and Sendmail with modular checker support, SQL logging, and web quarantine . **webmailMaquita** provides an AGPLv3 webmail and collaboration suite with outbound DLP (detecting national IDs, IBANs, credit cards), eDiscovery, legal hold, and active defense against compromised accounts . These tools cover the foundational gateway and compliance layers, though **no open-source alternative matches the AI-driven BEC detection** of Abnormal Security or the comprehensive suite breadth of Mimecast.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global email security market is estimated at **~$8B in 2026**, growing toward **~$20B by 2032**. The sector is **moderately fragmented** — **Proofpoint** leads on module breadth and enterprise adoption, **Mimecast** offers the most comprehensive suite (security + archiving + continuity + DLP), and **Abnormal Security** leads in AI-driven behavioral BEC detection . **Pricing varies dramatically**: Proofpoint Essentials starts at **$2.75/user/month** (Business tier) , Mimecast's 4,000-license UK government contract equated to **~£23.80/user/year** (~$2/user/month) , Barracuda Advanced is **$5.20/user/month** , IRONSCALES Protect starts at **$1.35/mailbox/month** (annual) , and Abnormal Security typically runs **$22–$35/employee/year** for small deployments . **Perception Point offers a genuinely free plan with unlimited users** . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Defender for Office 365](https://www.microsoft.com/en-us/security/business/office-365-defender)** | **Microsoft's native email security.** Anti-phishing, anti-spam, Safe Links, Safe Attachments, and attack simulation. Bundled with Microsoft 365 E5. | **Bundled with Microsoft 365 E5** (~$38/user/month for full suite). **Standalone Defender for Office 365 P1**: ~$2/user/month; **P2**: ~$5/user/month. | **No perpetual free tier**. **Microsoft 365 Business Basic** (~$6/user/month) includes basic Exchange Online Protection (EOP) anti-spam. | **~$281B revenue (Microsoft FY2025)** |
| **[Proofpoint Email Security](https://www.proofpoint.com/)** | **Enterprise email security leader.** Modular platform covering email filtering, DLP, threat intelligence, archiving, and security awareness training. | **Essentials Business**: **$2.75/user/month** (inbound/outbound filtering, URL Defense, Attachment Defense) . **Essentials Advanced**: **$3.75/user/month** (+ sandboxing, encryption) . **Essentials Professional**: **$5.33/user/month** (+ archiving) . Enterprise pricing is higher. | **No perpetual free tier**. **Free trial** available on request. | **Public (PFPT), ~$1B+ revenue est.** |
| **[Mimecast](https://www.mimecast.com/)** | **Comprehensive email management suite.** Security (Targeted Threat Protection), archiving, business continuity, DLP, and awareness training. | **Custom quote** — module-based. **Reference point**: UK government contract for 4,000 Mimecast 365 Protect licenses = **£95,188/year** (~£23.80/user/year, ~$2/user/month) . Enterprise bundles with archiving/DLP/continuity cost significantly more. | **No free tier**. **30-day trial** available. | **Private (~$1B+ revenue est.)** |
| **[Abnormal Security](https://abnormalsecurity.com/)** | **AI-native BEC detection.** API-based deployment (no gateway). Behavioral AI baselines normal communication patterns to detect sophisticated social engineering. | **$22–$35/employee/year** for small deployments (100–500 employees, 1-year contract) . **Multi-year deals**: **$18–$28/employee/year** . Mid-market (500–2,000 employees): **$18–$28/employee/year** . | **No free tier**. **Free trial** available. | **Private (~$4B valuation est.)** |
| **[Cisco Secure Email](https://www.cisco.com/)** | **Enterprise email gateway.** Formerly IronPort. Inbound/outbound protection with advanced malware analysis, URL filtering, and DLP. | **Custom enterprise pricing** — quote required. **Reference**: Cisco Services Portfolio Secure Email license = **$34,762.99** for a term license + support (CDW list) . **Email Advanced Term License** = **$13,939.99** (CDW list) . | **No free tier**. **Free trial** available. | **~$63B revenue (Cisco FY2025)** |
| **[Avanan (Check Point)](https://www.checkpoint.com/)** | **API-based cloud email security.** Protects Microsoft 365 and Google Workspace with advanced phishing, malware, and DLP. | **Per-user/year** pricing. **DMARC add-on**: **$14.93 per 100,000 emails/month** (moved from per-user to per-volume model July 2026) . **14-day POC** available. | **14-day trial** with full features, hard limit 100 users . **No perpetual free tier**. | **Part of Check Point (~$2.5B revenue)** |
| **[Barracuda Email Protection](https://www.barracuda.com/)** | **SMB and mid-market email security.** AI-powered phishing detection, BEC protection, and Microsoft 365 data protection. | **Advanced**: **$5.20/user/month** . **Premium**: **$8/user/month** (+ M365 data protection) . **Premium Plus**: **$10.50/user/month** (+ archiving) . | **No perpetual free tier**. **Free trial** available. | **Private (~$500M+ revenue est.)** |
| **[IRONSCALES](https://ironscales.com/)** | **AI-powered phishing remediation.** Community-powered threat intelligence and mailbox-level remediation. | **Protect**: **$1.35/mailbox/month** (annual) or **$1.50** (monthly) . **Email Protect**: **$4.39/mailbox/month** (annual) . **Complete Protect**: **$5.83/mailbox/month** (annual) . | **No free trial**. Month-to-month plans start at **10 mailboxes** with 30-day cancellation . | **Private (~$100M+ raised)** |
| **[Perception Point](https://perception-point.io/)** | **Next-gen email security ranked #1 in SE Labs testing.** 7 layers of detection for anti-spam, phishing, malware, BEC, and zero-day threats. | **Custom enterprise pricing** — quote required. | **Free Plan**: **Unlimited users**, any scale, no time limit. Covers inbound threats across Gmail, Microsoft 365, OneDrive, SharePoint, Teams, Google Drive, Dropbox, and Salesforce . | **Private (~$100M+ raised)** |
| **[Graphus](https://www.graphus.ai/)** | **Automated phishing defense for SMBs.** AI-driven protection for Microsoft 365 and Google Workspace. | **$3.00/month** starting price (Software Advice) . | **Free trial** available on request. | **Private (Graphus)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[Sagator](https://github.com/sagator/sagator)** — **Mature antivirus/anti-spam gateway for SMTP servers.** **GPLv2+** licensed. Modular architecture: combine any antivirus/spam checker (ClamAV, etc.) via configuration. Supports Postfix, Sendmail, and any SMTPD. Features: **MIME parsing and archive decompression**, **SQL logging**, **dynamic scanner configuration**, **daily reports**, **web quarantine** accessible to all users, **mailbox/maildir scanning and cleaning**, **SMTP policy service (greylist)**, and **nice statistics via WWW or MRTG**. No Perl modules required — pure Python . | [![Stars](https://img.shields.io/github/stars/sagator/sagator?style=social&color=white)](https://github.com/sagator/sagator/stargazers) | ~50 |
| **[webmailMaquita](https://github.com/wilson-arguello/webmailMaquita)** — **Open-source webmail and collaboration suite with enterprise-grade DLP and eDiscovery for self-hosted Postfix+Dovecot servers.** **AGPL-3.0** licensed. **Key features**: **Outbound DLP** detecting national ID numbers, tax IDs, IBANs, and payment card information (works with Outlook and mobile clients via milter) . **Anti-spoofing**: Detection of lookalike domains, homoglyphs, and impersonation of internal roles . **Active defense**: Automatic detection and containment of compromised accounts generating high-volume outbound email . **Compliance**: Forensic search across all mailboxes, legal holds, custodian management, GPG-signed email exports with RFC 3161 timestamping, and logging of 39 event types with end-to-end correlation (Postfix → Rspamd → Dovecot → user action) . **Stack**: React + FastAPI, 2FA TOTP, Dovecot mail_crypt encryption at rest, CalDAV/CardDAV, Kanban tasks, chat, and optional local AI via Ollama/Whisper . | [![Stars](https://img.shields.io/github/stars/wilson-arguello/webmailMaquita?style=social&color=white)](https://github.com/wilson-arguello/webmailMaquita/stargazers) | ~100 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Rspamd](https://github.com/rspamd/rspamd)** — Advanced spam filtering system with SPF/DKIM/DMARC, ML-based detection, and web UI. The de-facto choice for new mail infrastructure. |
| **[ClamAV](https://github.com/Cisco-Talos/clamav)** — Open-source antivirus engine for email virus scanning. Used by Sagator and most self-hosted mail stacks. |
| **[SpamAssassin](https://github.com/apache/spamassassin)** — Classic rule-based spam filter. Still actively maintained but Rspamd has become the default for new deployments. |
| **[Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway)** — Complete open-source email security solution with anti-spam, anti-virus, and quarantine. |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Email security platforms handle sensitive communications and PII; ensure compliance with GDPR, CCPA, and applicable data protection regulations.
- **Free tier caveats**: **Perception Point offers a genuinely free plan with unlimited users** (inbound protection only, limited IR access) . **IRONSCALES has no free trial** but offers month-to-month plans starting at 10 mailboxes . **Avanan offers a 14-day POC** with full features capped at 100 users . **Barracuda's pricing starts at $5.20/user/month** . **Proofpoint Essentials starts at $2.75/user/month** for basic filtering . **Abnormal Security has no free tier** and requires API integration .
- **Open-source reality**: The open-source ecosystem for email security is **focused on gateway filtering and DLP**. **Sagator** provides a mature antivirus/anti-spam gateway with modular checker support . **webmailMaquita** delivers enterprise-grade DLP, eDiscovery, and active defense for self-hosted Postfix+Dovecot environments . However, **commercial platforms** (Abnormal Security, Proofpoint, Mimecast) provide **AI-driven BEC detection, massive cross-customer threat intelligence networks, and comprehensive suite breadth** that open-source alternatives cannot match. The open-source path is **genuinely viable** for gateway filtering, DLP, and self-hosted compliance requirements.

---

**Made for security engineers, IT administrators, SOC analysts, and email infrastructure teams.**
Let's make email security more open, transparent, and effective.
