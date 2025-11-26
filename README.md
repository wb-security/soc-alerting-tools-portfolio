# SOC Alerting Tools — Public Portfolio Edition

This repository showcases a standardized **Security Operations Center (SOC)** alert processing framework based on real-world work in a managed services environment.

The goal of this project is to demonstrate:

- SOC alert triage & investigation workflows
- SIEM / EDR investigation structure (e.g., Rapid7-style flow)
- Client-facing communication templates
- Internal documentation and SOP design
- Time-entry frameworks compatible with ticketing/time-card systems
- Systems thinking applied to security operations

> All examples are fully fictionalized. Client names, IPs, domains, and logs are synthetic and used only for demonstration.

---

## 🎯 Audience

- **SOC Analysts (L1–L2)** looking for structured workflows and templates  
- **Team Leads / Managers** interested in standardizing SOC processes  
- **Recruiters & Hiring Managers** evaluating security operations maturity and documentation skills  

---

## 🧩 Repository Structure

- `primer/`  
  Core SOC Alert Processing Primer — end-to-end workflow description.

- `templates/`  
  Reusable templates for client emails and internal distribution list blurbs.

- `rapid7-note-templates/`  
  Investigation notes templates (start, update, closure) usable with any SIEM.

- `investigation-examples/`  
  Fully worked sample investigations with triage steps, findings, and outcomes.

- `client-communications/`  
  Example client notifications tied to the investigation examples.

- `time-entry/`  
  Time-entry framework and examples for documenting SOC work in time-card systems.

- `architecture/`  
  High-level architecture and data-flow diagrams for the SOC alerting process.

---

## 🔧 How to Use This Repository

### 1. As a SOC Analyst

Start with:

- `primer/SOC_Alert_Processing_Primer.md`  
- `templates/client-email-initial-notification.md`  
- `rapid7-note-templates/investigation-start.md`  

Adapt the language and patterns to your environment, SIEM, and ticketing systems.

### 2. As a Team Lead / Manager

Use this repo to:

- Standardize how analysts document investigations  
- Align client communications around consistent patterns  
- Onboard new analysts with a clear primer and concrete examples  

### 3. As a Recruiter / Hiring Manager

This project is designed to demonstrate:

- Ability to design and document **SOC workflows**  
- Attention to detail in **client communication**  
- Familiarity with **SIEM-driven investigations** and time tracking  
- Comfort building systems and frameworks, not just “closing tickets”

---

## 📚 Related Work

This SOC Alerting Tools repo pairs with a separate NOC-focused project:

- **NOC Alerting Tools — Public Portfolio Edition** (Network Operations workflows, OpsRamp-style monitoring)

---

## 📌 Disclaimer

All entities, logs, IPs, and domains in this repo are **fictional** and created solely for educational and portfolio purposes. Any resemblance to real organizations or environments is coincidental.

---

## 🧭 Roadmap

Planned enhancements:

- Additional investigation examples (cloud-focused, identity-focused, endpoint-focused)
- More advanced playbooks (password spray vs. MFA fatigue vs. impossible travel)
- Sample automation ideas and pseudo-code for alert enrichment

