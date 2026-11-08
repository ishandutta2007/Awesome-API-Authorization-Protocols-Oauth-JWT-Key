# Awesome-API-Authorization-Protocols-Oauth-JWT-Key

# Awesome-API-Authorization-Protocols-Oauth-JWT-Key

**Top API Authorization Protocols Oauth JWT Key (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on OAuth 2.0/OIDC Providers, JWT Validation, Passwordless Auth & Self-Hosted Identity Servers*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **API Authorization Protocols (OAuth/JWT/Key)**. These tools enable organizations to authenticate users and authorize API access using industry-standard protocols—OAuth 2.0, OpenID Connect, JWT, and key-based verification—from fully managed customer identity platforms with generous free tiers to self-hosted identity servers that give teams complete control over their login flows and token issuance.



**Examples** include Auth0, Okta, Ping Identity, Stytch, Clerk, FusionAuth, Descope, Keycloak, Ory Hydra, and Postman (the category leaders in commercial and open-source space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted OAuth/OIDC, JWT validation, and open identity infrastructure. **Critical note**: The open-source landscape is anchored by **Keycloak**—the default self-hosted identity server for years, with Apache 2.0 licensing and a mature administration model . **Ory Hydra** is the OpenID Certified OAuth 2.0/OIDC server for teams wanting to become an OAuth provider without adopting a new user model . **Casdoor** is the AI-native alternative with built-in MCP server and OAuth 2.1 support . No open-source project matches Auth0's developer experience or Okta's workforce integration depth, but for protocol implementation itself, the options are production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Identity and Access Management (IAM) and Customer IAM (CIAM) market is estimated at **$20B–$26B in 2024–2025** and projected to exceed **$30B by 2027**, compounding at an annual growth rate of 12%–16%. The industry exhibits a **moderately concentrated, bifurcated structure**: while massive enterprise workforce and CIAM deployments are dominated by a handful of consolidating giants (Okta/Auth0, Ping Identity/ForgeRock, Microsoft Entra ID), the developer-facing authentication, API authorization, and passwordless segments remain dynamic and moderately fragmented, with fast-growing specialized innovators (Clerk, Descope, Stytch, FusionAuth) capturing modern cloud-native and AI-agent workloads.

## SaaS/Hosted Platforms

| Platform | Company Scale (Valuation / Revenue) | Starting Paid Pricing | Free Tier Limits | Description & Best For | Trade-offs |
|---|---|---|---|---|---|
| **Okta** | **$15.3B Market Cap** ($2.61B ARR in FY2025) | Starter from **$6/user/month** (Essentials from $17/user/month; Workforce IAM) | **30-day free trial** (Includes SSO, Universal Directory, & Adaptive MFA for up to 100 test users; Integrator developer tier available) | Enterprise workforce identity, lifecycle management, and enterprise SSO alongside OAuth/OIDC. | Workforce-centric; customer identity is delegated to Auth0; complex enterprise procurement. |
| **Auth0** *(by Okta)* | **$6.5B Acquisition Valuation** (~$350M+ ARR at acquisition) | Essentials from **$35/month** (Professional from $240/month; Enterprise custom) | **Free forever up to 25,000 MAUs** (Unlimited social connections, basic MFA, custom domains, and community support) | Developer-friendly CIAM with polished OAuth 2.0/OIDC implementation, extensive SDKs, and Quickstarts. | Premium steep pricing curve as MAUs scale beyond entry tiers; CIAM focus rather than internal employee SSO. |
| **Postman** | **$5.6B Peak Valuation** (~$313M estimated ARR) | Solo from **$9/month** (Team collaboration from $19/user/month billed annually) | **Free forever for 1 user** (Unlimited collection runs, unlimited local/cloud mock servers, 1,000 API monitoring calls/mo, and 50–100 AI credits/mo; no team workspaces) | API client and platform with built-in OAuth 1.0/2.0, JWT, and API Key authorization debugging/testing. | Development & testing tool only; **not** a production authorization or token-issuing identity server. |
| **Ping Identity** *(incl. ForgeRock)* | **$2.8B Acquisition Value** (~$300M+ ARR when taken private by Thoma Bravo) | **Custom Enterprise Quote** (Annual contract starting at ~$20,000+/year) | **30-day free trial** (Full feature access to PingOne orchestration, SSO, MFA, and user directories in trial sandbox) | Complex enterprise customer journeys, federation, hybrid deployments, and advanced risk/fraud signals. | Heavier enterprise setup; lacks self-serve transparent micro-pricing tiers. |
| **Stytch** *(acquired by Twilio)* | **$1.0B Series B Valuation** (~$12M–$14M ARR; acquired by Twilio) | Usage-based starting at **$0/month base** ($0.05/MAU or $0.10/B2B member above free tier allowance) | **Free forever up to 10,000 MAUs** (Unlimited B2B orgs, up to 5 SSO/SCIM connections, 1,000 M2M tokens, 10,000 device fingerprints; no feature gating) | API-first passwordless authentication, passkeys, device fingerprinting, and agentic identity orchestration. | Acquired by Twilio; smaller third-party ecosystem compared to legacy Okta/Auth0 catalogs. |
| **Clerk** | **~$300M+ Valuation** (Series C raised $50M in late 2025; ~$15M–$30M ARR) | Pro from **$25/month** (Business from $300/month; Enterprise custom) | **Free forever up to 50,000 MRUs** (Monthly Retained Users; 3 admin seats, unlimited apps, custom domains, community support) | Prebuilt plug-and-play UI components for React, Next.js, and modern JS/TS web applications. | Primarily optimized for JavaScript/TypeScript stacks; less idiomatic for non-web backend protocols. |
| **Descope** | **~$210M–$500M Est. Valuation** ($88M total funding; ~$10M–$14M est. ARR) | Pro from **$249/month** (Growth from $799/month; Enterprise custom) | **Free forever up to 7,500 MAUs** (Up to 10 tenants, 3 SSO connections, drag-and-drop workflow canvas, passwordless & MFA) | Visual no-code drag-and-drop authentication and authorization flow orchestration with fraud defense. | Newer platform; deep custom logic edge-cases may require code hooks outside visual designer. |
| **FusionAuth** | **~$150M–$250M Est. Valuation** ($65M growth equity round; ~$15M–$30M est. ARR) | Starter Cloud from **$162/month** (Essentials from $2,970/month; Enterprise custom) | **Free forever with Unlimited MAUs** (Self-hosted Community Edition on Docker/Kubernetes/bare-metal with full OAuth/OIDC/SAML support) | Self-hostable or dedicated single-tenant cloud identity platform with predictable, volume-agnostic pricing. | Cloud tiers require baseline monthly spend; self-hosted free tier requires self-managing databases and upgrades. |

## Open-Source GitHub Projects



- **Keycloak**

  **Open-source identity and access management server** (Apache 2.0) — **the default self-hosted IdP for years**, with a mature administration model and broad protocol coverage . **Features**: **OAuth 2.0, OIDC, and SAML 2.0** provider; **LDAP/Active Directory federation** natively; **themed login pages**; **admin console**; **user federation and live LDAP lookups**; **SCIM 2.0 support** (since 26.8) ; **authentication flows** with Java SPI extension points. **Tech stack**: Java (Quarkus). **Deploy**: Self-hosted (binary, Docker, Kubernetes). **Trade-off**: **Java overhead**—heavier than Go-based alternatives; theming and upgrades require care ; some newest features (SCIM, AuthZEN, Admin API v2) are preview or experimental . **Best for**: teams wanting a working identity system on day one with enterprise directories, non-engineer administrators, or a small team .



- **Ory Hydra**

  **OpenID Certified OAuth 2.0 and OIDC server** (Apache 2.0) — **the best choice for becoming an OAuth provider without adopting a new user model** . **Features**: **OpenID Certified**—matters if you are an OAuth provider for third parties ; **headless by design**—no forced user management or login UI; plug in Kratos or your existing user store ; **OAuth 2.0 and OIDC** token issuance and delegation; part of the Ory ecosystem (Kratos for identity, Keto for permissions, Oathkeeper for proxy). **Tech stack**: Go. **Deploy**: Self-hosted (Docker, Kubernetes) or Ory Network. **Trade-off**: **Headless means you build the login, registration, consent, and settings UI yourself** ; running multiple Ory services is more moving parts than a single IdP ; open-source releases can sit long between patches—Enterprise License sells CVE patching with SLA . **Best for**: product teams wanting full control of the login UI and comfortable assembling identity from APIs—especially those who only need OAuth/OIDC, not a full user management system .



- **Casdoor**

  **AI-native IAM/SSO platform** (Apache 2.0) — **the most modern open-source identity server with built-in MCP support** . **Features**: **OAuth 2.0/OIDC, SAML 2.0, CAS, LDAP server, RADIUS server**—all built in ; **MCP server and OAuth 2.1 for MCP** built in—no other major open-source IdP has this ; **70+ social/enterprise providers** including WeChat, DingTalk, Lark, Alipay, Google, GitHub, Microsoft ; **everything configured in web UI**—login pages, fields, providers, themes ; **syncers** for Keycloak, Okta, Entra ID, Active Directory, Google Workspace, AWS IAM ; **Casbin policy engine** for ACL/RBAC/ABAC ; **single Go binary**—no JVM, no separate worker . **Tech stack**: Go, React UI. **Deploy**: Self-hosted (single binary) or Casdoor Cloud ($29/month, $20 free credit) . **Trade-off**: **Smaller community than Keycloak**—fewer Stack Overflow answers and third-party tutorials . **Best for**: teams wanting broad protocol coverage (including MCP for AI agents) in a modern, UI-first self-hosted platform—especially those building AI-integrated applications .



- **Zitadel**

  **Cloud-native identity management platform** (AGPL-3.0) — **the Kubernetes-native alternative** with clean multi-tenancy . **Features**: **OAuth 2.0/OIDC and SAML 2.0** provider; **multi-tenancy via Instances and Organizations**—clean isolation for external users/contractors ; **self-service portal** for users to manage credentials and MFA; **API-first design**; **Go-based** for low resource usage. **Tech stack**: Go, TypeScript login UI, PostgreSQL. **Deploy**: Self-hosted (Helm, Kubernetes). **Trade-off**: **AGPL license**—copyleft obligations if you modify and distribute; **smaller community than Keycloak** . **Best for**: small businesses and platform teams deploying in containerized/Kubernetes environments where resource efficiency matters—especially those managing external users as separate tenants .



### Additional Strong Open-Source Options



- **Authentik** — Open-source IdP with the most flexible sign-in flow engine (MIT core, enterprise features commercial) . **Features**: Flows and stages edited in admin interface; proxy provider for Traefik/Caddy/Nginx/Envoy; LDAP source sync; SCIM source . **Note**: **Separate tenants are an alpha enterprise feature**—multi-tenancy is via Brands for branding, not full isolation . **Best for**: teams wanting a modern, clean IAM with excellent user self-service and flexible flows—especially those frustrated by Keycloak's UI .

- **Logto** — Application IAM with authentication and authorization (MPL-2.0 core) . **Features**: Cloud or self-hosted; application-oriented SDK and protocol integration; OAuth 2.1 for MCP servers . **Note**: **Smaller community** than Keycloak or Ory; less enterprise validation. **Best for**: teams wanting a modern application IAM with MCP support.



**Frameworks for building custom systems**: Choose **Keycloak** for a working identity system out of the box with enterprise directory support, **Ory Hydra** for OAuth/OIDC only without adopting a user model, and **Casdoor** for broad protocol coverage including MCP . **None match Auth0's developer experience or Okta's workforce integration depth**, but for protocol implementation itself, the options are production-proven.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Authorization platforms handling credentials and tokens must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls. **OAuth and OIDC implementations must follow the specifications correctly**—misconfiguration is a common breach vector.

- **The "full identity server" vs. "headless OAuth server" vs. "CIAM platform" vs. "workforce IdP" distinction is critical.** **Keycloak, Casdoor, Zitadel, and Authentik** are **full identity servers**—they provide login pages, admin consoles, and user management alongside OAuth/OIDC . **Ory Hydra** is a **headless OAuth server**—it handles token issuance and delegation without forcing a user model . **Auth0, Clerk, Stytch, and Descope** are **CIAM platforms**—they optimize for customer-facing login with generous free tiers . **Okta and Ping** are **workforce IdPs**—they focus on employee SSO and lifecycle management . **Choose based on whether you need full user management, headless OAuth, customer login, or workforce SSO.**

- **Keycloak is the safest default for self-hosted identity**—working login pages on the first afternoon, LDAP federation, and monthly patch releases . **The trade-off**: Java overhead; theming and major upgrades require care .

- **Ory Hydra is for teams who only need OAuth/OIDC.** It is OpenID Certified and headless—you bring your own user store and build your own login UI . **The trade-off**: more integration work; open-source releases can sit long between patches, with CVE patching under Enterprise License .

- **Casdoor is the most modern option for AI-agent integration**—built-in MCP server and OAuth 2.1 for MCP, plus CAS/LDAP/RADIUS servers that Keycloak lacks without extensions . **The trade-off**: smaller community than Keycloak.

- **Auth0's free tier and $35/month entry are the most accessible commercial CIAM**; Clerk's Hobby plan is free, Pro at $25/month . **For small teams, these are the pragmatic starting points.**

- **Postman's free tier became single-user only in March 2026**—no team collaboration, no shared workspaces . **Do not plan team API auth management on the free tier.**

- Self-hosted open-source solutions require proper infrastructure (Java for Keycloak, Go for Ory/Casdoor/Zitadel, Python for Authentik) and ongoing maintenance. **Identity servers are the keys to your kingdom**—ensure your deployment meets your organization's security and compliance requirements before issuing production tokens.



---



**Made for identity engineers, API developers, and organizations building transparent authorization protocol solutions.**

Let's make API Authorization Protocols more open, data-driven, and token-safe.
