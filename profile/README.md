# eSMS Africa

**Reliable SMS & Email infrastructure for Africa.**

We provide Bulk SMS, OTP delivery, SMPP connectivity, HTTP APIs, and transactional email services — powering businesses across 28+ African countries.

---

### What We Build

**SMS Platform** — Send campaigns, manage contacts, automate OTP delivery, and integrate via REST API or SMPP protocol.

**Email Platform** — Transactional email with custom domains, DKIM signing, bounce monitoring, and SMTP relay.

**SMPP Gateway** — Direct SMPP connectivity with real-time connector management, message routing, and delivery tracking.

---

### Our Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | FastAPI (Python), Spring Boot (Java 21) |
| **Frontend** | SvelteKit, Vue 3, Tailwind CSS |
| **Messaging** | Postfix, OpenDKIM, RabbitMQ, Jasmin SMPP |
| **Data** | PostgreSQL, Redis |
| **Infra** | AWS, Docker, GitHub Actions CI/CD |

---

### Repositories

#### SMS Platform
| Repo | Description |
|------|-------------|
| [patrol-esms](https://github.com/eSMS-Africa/patrol-esms) | Spring Boot backend — SMS routing, billing, SMPP/HTTP APIs |
| [brazen-esms](https://github.com/eSMS-Africa/brazen-esms) | Client portal — campaigns, contacts, sender IDs, payments |
| [intrepid-esms](https://github.com/eSMS-Africa/intrepid-esms) | Admin dashboard — user management, wallets, monitoring |

#### Email Platform
| Repo | Description |
|------|-------------|
| [smtp-api](https://github.com/eSMS-Africa/smtp-api) | FastAPI backend — email API, Postfix/DKIM, bounce tracking |
| [smtp-ui](https://github.com/eSMS-Africa/smtp-ui) | SvelteKit frontend — domains, analytics, forwarding |

#### SMPP Gateway
| Repo | Description |
|------|-------------|
| [jasmin-client-manager](https://github.com/eSMS-Africa/jasmin-client-manager) | Gateway API — connectors, routes, user provisioning |
| [jasmin-client-ui](https://github.com/eSMS-Africa/jasmin-client-ui) | Gateway dashboard — real-time monitoring, terminal |

#### Authentication
| Repo | Description |
|------|-------------|
| [esms-auth](https://github.com/eSMS-Africa/esms-auth) | Central auth — JWT SSO, registration, email verification |
| [esms-auth-ui](https://github.com/eSMS-Africa/esms-auth-ui) | Auth UI — login, registration, password reset |

#### Website
| Repo | Description |
|------|-------------|
| [esmsafrica.io](https://github.com/eSMS-Africa/esmsafrica.io) | Landing page and marketing website |

---

[esmsafrica.io](https://esmsafrica.io)
