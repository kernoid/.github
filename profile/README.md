<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/kernoid-lockup-on-dark.svg">
    <img src="assets/kernoid-lockup-on-light.svg" alt="kernoid" width="480">
  </picture>
</p>

<p align="center"><b>One core for email, identity and storage.</b><br>
<sub>a <a href="https://falkoss.org">falkOSS</a> project</sub></p>

**kernoid** is one self-hostable system for an organisation's core: an account is created once and is at the same
time the mailbox, the login for single sign-on and the owner of files. Free software in Rust – everything included.

> kernoid is at its beginning: there is nothing to install yet. Start with the
> [whitepaper](https://github.com/kernoid/whitepaper).

### What it is

- **One identity** – mailbox, login and file owner are the same object; leaving ends access everywhere in one step.
- **One administration** – users, groups, domains, roles and policies in one place, one interface, one API.
- **One operation** – one container image on Docker or Kubernetes, with PostgreSQL and S3-compatible storage.
- **Open standards** – SMTP, IMAP, JMAP, CalDAV, CardDAV, WebDAV; OpenID Connect, OAuth 2.0, SAML 2.0, SCIM 2.0, LDAP.
- **Built on proven work** – AGPL code from [Stalwart](https://github.com/stalwartlabs/stalwart), concepts from
  [Zitadel](https://github.com/zitadel/zitadel), credited in every file.

### Same rules as falkOSS

- **Free licences** – the server under the AGPL-3.0, first-party apps under MIT.
- **Everything included** – one edition, every feature free; no paid tiers, nothing held back.
- **No telemetry** – nothing phones home.
- **In the open** – issues, plans, reviews and decisions happen in public.

### Repositories

| Repository | What |
|---|---|
| [whitepaper](https://github.com/kernoid/whitepaper) | the whitepaper – Markdown, set to PDF with Typst |
| [kernoid](https://github.com/kernoid/kernoid) | the software (not started yet) and the brand kit |
| [website](https://github.com/kernoid/website) | the landing page |

### Contribute

Open an issue or a pull request in the repository you care about – contributions are accepted under the
[Developer Certificate of Origin](https://developercertificate.org). For anything else:
[falkoss.org](https://falkoss.org) · [support@falkoss.org](mailto:support@falkoss.org)
