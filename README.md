# Awesome-Directory-Synchronization-SSO

## Top Directory Synchronization & SSO Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Identity Federation, User Provisioning & Single Sign-On*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Directory Synchronization & SSO**. These tools enable organizations to centralize identity management, synchronize user directories across systems, and provide Single Sign-On access to applications — reducing password fatigue and improving security posture.



**Examples** include Salesforce Identity Connect, Okta Universal Directory, Microsoft Entra Connect, JumpCloud Directory Insights, OneLogin Desktop, PingFederate, DualShield, miniOrange SSO, Rippling Identity, and Google Cloud Identity (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom identity federation, and open directory synchronization — ideal for organizations seeking transparent, vendor-independent identity infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Identity and Access Management (IAM) and Single Sign-On (SSO) market is estimated at **$24B–$27B in 2026** (with the dedicated enterprise SSO segment representing approximately **$4.5B–$5.5B**), growing at an annual rate of 12%–14%. The sector exhibits an **oligopolistic, highly concentrated structure at the enterprise core**—dominated by hyperscalers and dedicated platform giants like Microsoft Entra ID and Okta—alongside **moderate fragmentation across specialized tiers**, where emerging SaaS vendors and open-source stacks cater to hybrid directory syncing, CIAM, and decentralized protocol workflows.



## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Market Cap / Revenue) | Description | Pricing (Starting Tier) | Free Tier Limits / Trial |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Entra Connect](https://www.microsoft.com/en-us/security/business/)** | ~$3.1T Market Cap (Microsoft; >$245B Annual Revenue) | Synchronizes on-premises Active Directory with Microsoft Entra ID (Azure AD). Enables hybrid identity, password hash sync, pass-through authentication, and seamless SSO. | Free sync tool included; Entra ID P1 starts at $6.00 per user/month | Free forever plan included with Microsoft cloud services (up to 50,000 directory objects, or 300,000 with custom domain; core SSO & MFA) |
| **[Google Cloud Identity](https://cloud.google.com/identity)** | ~$2.1T Market Cap (Alphabet; >$350B Annual Revenue) | Cloud-native identity platform with directory sync from AD/LDAP, SSO, MFA, and device management. Integrates with Google Workspace and GCP. | $6 per user/month (Cloud Identity Premium edition) | Free forever plan (Cloud Identity Free includes up to 50 user licenses, SSO, MFA, and AD/LDAP directory sync) |
| **[Salesforce Identity Connect](https://help.salesforce.com/)** | ~$280B Market Cap (Salesforce; >$38B Annual Revenue) | Synchronizes users and groups from Active Directory to Salesforce. Enables SSO via SAML and automates user provisioning/deprovisioning based on AD group membership. | $1 per user/month (billed annually as Enterprise/Performance/Unlimited edition add-on) | 30-day trial (standard Salesforce trial); Developer Edition includes 10 Identity Connect licenses free forever |
| **[Rippling Identity](https://www.rippling.com/)** | $13.5B Valuation (Private; ~$350M+ ARR) | Unified identity and device management platform. Features HRIS-driven provisioning, SSO, and automated onboarding/offboarding workflows. | $8 per user/month (Unity base platform + $6 per user/month for Identity/App Management module) | 14-day free trial (available for IT Cloud & Identity Management modules upon demo verification) |
| **[Okta Universal Directory](https://www.okta.com/)** | ~$12B Market Cap (Okta; ~$2.6B Annual Revenue) | Centralized identity store supporting any number of user attributes and custom schemas. Features directory integration, profile mastering, and lifecycle management across apps. | $6 per user/month (Workforce Starter Suite; $1,500/year contract minimum) | 30-day free trial (fully functional workforce sandbox up to 100 users, no credit card required) |
| **[PingFederate](https://www.pingidentity.com/)** | $2.8B Acquisition Valuation (Thoma Bravo; ~$350M+ ARR) | Enterprise federation server supporting SAML, OAuth, OIDC, and WS-Fed. Features identity bridging, attribute mapping, and high-availability clustering. | $3 per user/month (PingOne Workforce Essential; enterprise on-prem PingFederate deployments start at ~$50,000/year) | 30-day free trial (PingOne cloud evaluation sandbox supporting up to 1,000 active identities) |
| **[JumpCloud Directory Insights](https://jumpcloud.com/)** | $2.6B Valuation (Private; ~$150M+ ARR) | Cloud-based directory platform with event logging and audit trails. Features cross-platform user management, device management, and SSO across cloud and on-prem resources. | $9 per user/month (Device Management; SSO Package starts at $11 per user/month billed annually) | 30-day free trial (full platform access with all premium features and directory sync; no credit card required) |
| **[OneLogin Desktop](https://www.onelogin.com/)** | ~$500M Acquisition Estimate (One Identity / Quest Software; ~$60M ARR) | Desktop SSO solution for Mac and Windows. Provides seamless login to cloud apps and on-prem resources with MFA enforcement. | $2 per user/month (Starter SSO package billed annually) | 30-day free trial (unlimited app connections, desktop SSO, MFA, and cloud directory integration) |
| **[miniOrange SSO](https://www.miniorange.com/)** | Bootstrapped / Private (~$18M Annual Revenue) | Affordable SSO and MFA solution for cloud and on-prem apps. Supports SAML, OAuth, JWT, and directory sync. | $1.50 per user/month (Cloud IAM Essential SSO plan) | Free forever plan for small environments (up to 500 users with basic SSO/directory sync); 30-day free trial for premium enterprise tier |
| **[DualShield](https://www.deepnetsecurity.com/)** | Privately Held / Niche (~$3M–$5M Annual Revenue) | Enterprise authentication platform with SSO, MFA, and directory integration. Supports AD, LDAP, and RADIUS with flexible policy controls. | $1.50 per user/month (estimate based on minimum 100-user enterprise license tiers via reseller channels) | 30-day free trial (available upon proof-of-concept request for on-prem/private cloud evaluation) |



## Open-Source GitHub Projects



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Leading open-source identity and access management platform (Apache-2.0), a CNCF project. Features SSO, social login, MFA, LDAP/AD integration, SAML, OIDC, and a comprehensive admin console. Robust clustering for high availability .



- **[ZITADEL](https://github.com/zitadel/zitadel)**  

  Open-source identity infrastructure (Apache-2.0) built for multi-tenancy. Features SSO, MFA, Passkeys, OIDC, SAML, SCIM, LDAP, and comprehensive audit trail via immutable event stream. API-first with gRPC, connectRPC, and REST .



- **[Authentik](https://github.com/goauthentik/authentik)**  

  Open-source Identity Provider (MIT) for modern SSO. Supports SAML, OAuth2/OIDC, LDAP, RADIUS, and more. Designed for self-hosting from small labs to large production clusters. User-friendly interface simplifies complex identity tasks .



- **[Ory](https://github.com/ory)**  

  Modular, cloud-native identity stack (Apache-2.0). Components include Ory Kratos (identity management), Ory Hydra (OAuth2/OIDC), and Ory Keto (authorization). API-first design optimized for Kubernetes and headless implementations .



- **[FusionAuth](https://github.com/FusionAuth/fusionauth)**  

  Developer-focused identity platform (Apache-2.0 for community). Features SSO, MFA, social login, advanced registration forms, and extensive API/SDK support. Engineered to handle millions of users with horizontal scaling .



- **[Nubus](https://github.com/univention/nubus)**  

  Modular open-source IAM solution (AGPL-3.0) for organizations and software stacks. Features central web portal, SSO, self-service functions, and prebuilt integrations for common systems. Supports Kubernetes, on-premises, and hybrid deployment .



- **[Logto](https://github.com/logto-io/logto)**  

  Open-source identity and access management (MPL-2.0) for modern apps. Features OIDC, SAML, social login, MFA, RBAC, and organization-scoped login. Self-hostable via Docker Compose with management API for user migration .



- **[Kivraid](https://github.com/kivraid/kivraid)**  

  Lightweight open-source identity provider (license varies) shipped as a single static Go binary with embedded SQLite. Features OIDC provider, forward auth, LDAP, TOTP, passkeys, admin console, and audit trail. Idles at ~26 MB RAM .



- **[LSC (LDAP Synchronization Connector)](https://github.com/Worteks/lsc)**  

  Open-source directory synchronization tool (BSD license) written in Java. Reads from databases, LDAP directories, or files and transforms/compares data to an LDAP directory. Features powerful scripting engine (JavaScript, Groovy) for on-the-fly data manipulation and Active Directory-specific functions .



- **[ssoready](https://github.com/ssoready/ssoready)**  

  Open-source developer tools for enterprise SSO (MIT). Ship SAML + SCIM support quickly. Includes SDKs for multiple languages .



- **[BoxyHQ Jackson](https://github.com/boxyhq/jackson)**  

  Open-source SSO service (Apache-2.0) supporting SAML and OpenID Connect. Also supports Directory Sync via SCIM 2.0 for automatic user and group provisioning/deprovisioning .



- **[MaxKey](https://github.com/dromara/MaxKey)**  

  Leading IAM/IDaaS product (Apache-2.0). Supports OAuth2.x, OIDC, SAML2.0, CAS, JWT, SCIM and other SSO standard protocols. RBAC-based unified permission control with user lifecycle management .



- **[OpenAM](https://github.com/OpenIdentityPlatform/OpenAM)**  

  Open-source access management solution (CDDL) including authentication, SSO, authorization, federation, entitlements, and web services security .



- **[Hanko](https://github.com/teamhanko/hanko)**  

  Open-source authentication and user management (AGPL-3.0). Focus on passkeys, with support for social logins, SAML SSO, MFA (TOTP, security keys), and OAuth SSO. API-first with small footprint .



### Additional Strong Open-Source Options



- **[SimpleSAMLphp](https://github.com/simplesamlphp/simplesamlphp)** — Native PHP authentication application (LGPL-2.1) for SAML federation .

- **[pac4j](https://github.com/pac4j/pac4j)** — Security engine for Java (Apache-2.0) supporting OAuth, CAS, SAML, OIDC, LDAP, JWT .

- **[caddy-security](https://github.com/greenpau/caddy-security)** — Authentication/authorization plugin for Caddy v2 with SAML, OIDC, LDAP, MFA support .

- **[privacyIDEA](https://github.com/privacyidea/privacyidea)** — Multi-factor authentication system (AGPL-3.0) with OTP server .

- **[slashtags](https://github.com/slashdevops/idp-scim-sync)** — Sync AWS SSO groups/users with Google Workspace directory .

- **[Gravitee Access Management](https://github.com/gravitee-io/gravitee-access-management)** — Open-source IAM solution (Apache-2.0) .

- Community **awesome-auth** list for comprehensive AuthN+Z resources .



**Frameworks for building custom systems**: Combine **Keycloak** or **ZITADEL** as the core IdP with **LSC** for directory synchronization, **BoxyHQ Jackson** for SCIM provisioning, **Hanko** for passkey-first authentication, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade identity platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity platforms handling authentication data must comply with security regulations (SOC 2, GDPR, ISO 27001, etc.).

- Self-hosted open-source solutions require proper security hardening, certificate management, and ongoing maintenance. Identity infrastructure is security-critical and should be deployed with appropriate expertise.



---



**Made for identity architects, IT administrators, security engineers, and developers building transparent directory synchronization and SSO solutions.**  

Let's make Directory Synchronization & SSO more open, secure, and interoperable.
