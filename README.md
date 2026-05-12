# CNE Portfolio Website

## Overview

This project is a lightweight professional portfolio website focused on:

- Cloud Engineering
- Azure Infrastructure
- Cloud Networking
- Infrastructure Automation
- Cybersecurity
- AI Operations
- Infrastructure-as-Code (IaC)

The website is intentionally designed to be:

- lightweight
- fast
- low-cost
- easy to maintain
- operationally simple
- highly portable

The architecture avoids unnecessary backend systems and complex deployment pipelines.

---

# Live URLs

## Production

- https://vedicdog.com
- https://www.vedicdog.com

## Azure Static Web App Host

- https://white-bush-008a92d10.2.azurestaticapps.net

---

# Final Architecture

```text
Users
  ↓
Azure Static Web Apps (Free Tier)
  ↓
Static HTML/CSS Portfolio
```

---

# Technology Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript

No frontend frameworks are used:

- No React
- No Angular
- No Vue
- No build pipeline
- No npm dependencies
- No backend APIs

---

# Hosting

## Azure Static Web Apps

Hosting platform:

```text
Azure Static Web Apps (Free Tier)
```

Azure Static Web App resource:

```text
swa-kerget-portfolio
```

Deployment model:

```text
GitHub
  ↓
Azure Static Web Apps
```

---

# Custom Domains

## Active Domains

```text
vedicdog.com
www.vedicdog.com
```

Azure automatically provisions and manages SSL/TLS certificates.

---

# Previous Architecture (Retired)

The original hosting architecture used:

```text
Azure Front Door
+ Azure Blob Static Website
```

This architecture was retired in favor of Azure Static Web Apps.

Removed components:

- Azure Front Door
- Azure WAF
- Blob Static Website hosting

Reason for migration:

- reduce monthly cost
- simplify operations
- remove unnecessary enterprise edge infrastructure
- reduce maintenance complexity
- simplify DNS and SSL management

---

# Repository Structure

```text
cne-portfolio/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
├── README.md
│
├── assets/
│   ├── css/
│   │   └── style.css
│   │
│   ├── images/
│   │   └── hero-bg.jpg
│   │
│   └── docs/
│       └── resume.pdf
```

---

# Local Development

Primary local project directory:

```text
C:\cne-portfolio
```

---

# Design Philosophy

The portfolio intentionally prioritizes:

- simplicity
- readability
- professionalism
- fast loading speed
- mobile responsiveness
- minimal operational overhead

The project intentionally avoids overengineering.

---

# Visual Design

## Style Characteristics

The UI follows a clean modern consulting-style aesthetic.

Characteristics:

- responsive layout
- large content sections
- clean typography
- lightweight styling
- professional infrastructure-focused branding
- low visual clutter

---

# Core Pages

## Home

```text
index.html
```

Main landing page introducing:

- cloud engineering background
- Azure expertise
- infrastructure focus
- consulting direction

---

## About

```text
about.html
```

Professional background and experience overview.

---

## Projects

```text
projects.html
```

Showcases:

- Azure projects
- infrastructure work
- automation work
- AI platform initiatives
- IaC implementations

---

## Contact

```text
contact.html
```

Contact and professional inquiry page.

---

# Assets

## CSS

Primary stylesheet:

```text
assets/css/style.css
```

---

## Images

Primary image assets:

```text
assets/images/
```

---

## Resume

Professional resume PDF:

```text
assets/docs/resume.pdf
```

---

# Deployment Model

## GitHub Integration

The portfolio is deployed directly from GitHub.

Deployment flow:

```text
GitHub Repository
  ↓
Azure Static Web Apps
  ↓
Custom Domains
```

Automatic deployments occur after GitHub pushes.

---

# DNS Configuration

## GoDaddy DNS

Current DNS configuration:

### WWW Domain

```text
CNAME
www → white-bush-008a92d10.2.azurestaticapps.net
```

### Root Domain

```text
vedicdog.com
→ forwarding → www.vedicdog.com
```

This configuration simplifies:

- SSL management
- DNS routing
- browser compatibility
- Azure SWA integration

---

# SSL/TLS

SSL certificates are automatically managed by Azure Static Web Apps.

No manual certificate management is required.

---

# Infrastructure Evolution

## Original Direction

Originally:

```text
kerget.com
→ hosted portfolio
```

After migration:

```text
vedicdog.com
→ portfolio

kerget.com
→ reserved for future AI/company platform
```

This separation allows:

- cleaner branding
- business platform separation
- dedicated AI platform domain strategy

---

# Operational Philosophy

This project intentionally avoids:

- backend APIs
- server-side rendering
- containers
- Kubernetes
- unnecessary frameworks
- complex CI/CD pipelines
- infrastructure overengineering

Core philosophy:

```text
Operationally simple and maintainable.
```

Goals:

- low cost
- high reliability
- easy maintenance
- easy portability
- fast recovery

---

# Backup Strategy

Recommended backups:

- GitHub repository
- local project copy
- resume PDF backup
- asset backups

---

# Recovery Strategy

Recovery process is intentionally simple:

1. Restore repository
2. Reconnect Azure Static Web App
3. Reconfigure custom domains if necessary
4. Azure automatically reprovisions SSL

---

# Mobile Responsiveness

The site is designed to support:

- desktop
- laptop
- tablet
- mobile browsers

Responsive behavior is handled through CSS.

---

# Security Considerations

The website intentionally minimizes attack surface by:

- avoiding backend services
- avoiding public APIs
- avoiding server-side code
- serving static content only

This significantly reduces:

- maintenance burden
- infrastructure risk
- operational complexity

---

# Future Roadmap

Potential future enhancements:

- AI consulting landing pages
- Azure architecture case studies
- Infrastructure automation demos
- cybersecurity articles
- AI operations content
- Terraform/IaC showcases
- embedded AI demos
- consulting intake workflows

---

# Strategic Direction

The portfolio is evolving toward:

```text
Cloud Infrastructure
+ AI Operations
+ Automation
+ Security
```

The long-term goal is to position the platform for:

- consulting
- infrastructure services
- AI operational systems
- cloud automation
- agentic infrastructure tooling

---

# Current Status

## Fully Operational

Working components:

- Azure Static Web Apps hosting
- GitHub deployment
- Custom domains
- HTTPS/SSL
- Mobile responsiveness
- Portfolio pages
- Resume hosting
- Asset delivery

---

# Important Notes

## Front Door Retirement

Azure Front Door was intentionally removed to:

- reduce recurring cost
- simplify architecture
- remove unnecessary enterprise infrastructure

This migration successfully preserved:

- custom domains
- HTTPS
- GitHub deployment
- public availability

while significantly simplifying the platform.

---

# Licensing

Private portfolio project.

Not intended as a public open-source application.

---

# Author

Dima Kerget

Cloud Network Engineer

Specializations:

- Azure
- Cloud Infrastructure
- Cloud Networking
- Infrastructure Automation
- Cybersecurity
- AI Operational Systems

---

# Final Philosophy

The project intentionally favors:

- practical engineering
- simplicity
- operational efficiency
- low maintenance
- scalable direction without unnecessary complexity

The architecture succeeds because it uses only the infrastructure required for the actual business need.

