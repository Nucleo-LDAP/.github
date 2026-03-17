<div align="center">

<img src="https://raw.githubusercontent.com/NucleoLDAP/nucleo-ldap/main/assets/logo.png" alt="Nucleo LDAP" width="120" />

# Nucleo LDAP --DRAFT--

**The modern, self-hostable web UI for LDAP administration.**  
Manage users, groups & organizational units on any LDAPv3 server — clean, fast, open source.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-under%20active%20development-orange)]()
[![NestJS](https://img.shields.io/badge/Backend-NestJS-red?logo=nestjs)](https://nestjs.com)
[![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?logo=next.js)](https://nextjs.org)
[![.NET Aspire](https://img.shields.io/badge/Orchestration-.NET%20Aspire-purple?logo=dotnet)](https://learn.microsoft.com/dotnet/aspire)

</div>

---

## Why Nucleo?

Existing LDAP management tools are either outdated (phpLDAPadmin),
too complex (FusionDirectory), or too limited (lldap's built-in UI).  
**Nucleo** is built for homelab admins, self-hosters or small organizations who want a
modern, lightweight, and Docker-friendly alternative.

- 🌲 **Generic** — connects to any LDAPv3-compatible server (OpenLDAP, 389DS, lldap)
- ⚡ **Fast & modern** — built with Next.js and NestJS, no legacy stack
- 🔒 **Secure by default** — LDAPS/TLS, JWT auth, full audit log
- 🐳 **Self-hostable** — single `docker compose up` to get started
- 🧩 **Adapter-based** — clean hexagonal architecture, easy to extend

---

## What you can do with Nucleo

| Feature                          | V1  |
| -------------------------------- | :-: |
| List, create, edit, delete users | ✅  |
| Reset & manage passwords         | ✅  |
| Manage groups & memberships      | ✅  |
| Connect to any LDAPv3 server     | ✅  |
| LDAPS / TLS support              | ✅  |
| Audit log                        | ✅  |
| Dynamic schema introspection     | ✅  |
| Multi-server profiles            | 🔜  |
| Active Directory support         | 🔜  |
| DIT tree explorer                | 🔜  |

---

## Stack

| Layer             | Technology                      |
| ----------------- | ------------------------------- |
| Frontend          | Next.js 15 · TypeScript · React |
| Backend           | NestJS · Fastify · TypeScript   |
| LDAP client       | ldapts                          |
| Dev orchestration | .NET Aspire                     |
| LDAP (dev)        | bitnami/openldap                |

---

## Getting Started

```bash
git clone https://github.com/NucleoLDAP/nucleo-ldap
cd nucleo-ldap
cp .env.example .env
docker compose up
```

> Open [http://localhost:3000](http://localhost:3000) and connect to your LDAP server.

---

## Repositories

| Repo                                                               | Description                                |
| ------------------------------------------------------------------ | ------------------------------------------ |
| [nucleo-ldap](https://github.com/NucleoLDAP/nucleo-ldap)           | Main monorepo — backend, frontend, AppHost |
| [nucleo-ldap-docs](https://github.com/NucleoLDAP/nucleo-ldap-docs) | Documentation                              |

---

## Contributing

Nucleo is in active development and welcomes contributions of all kinds —  
bug reports, feature requests, code, or documentation.

👉 Read the [Contributing Guide](https://github.com/NucleoLDAP/.github/blob/main/CONTRIBUTING.md)  
💬 Open an [Issue](https://github.com/NucleoLDAP/nucleo-ldap/issues)  
📬 Contact: nucleo.ldap@proton.me

---
