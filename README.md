# 🐄 PashuSetu — Livestock Health Command Centre

### Farm to Lab to Command Centre | An Early Warning System for Livestock

**PashuSetu** is a livestock health surveillance and decision-support platform designed to help farmers, veterinarians, para-veterinary workers, and government departments identify potential animal disease outbreaks earlier, monitor village-level risks, and coordinate timely responses.

The project aims to bridge the gap between farmers, veterinary services, diagnostic laboratories, and public health authorities through a unified, data-driven dashboard.

> **Project:** Smart India Hackathon (SIH) 2026
> **Problem Statement ID:** 26128
> **Theme:** Health / Biotech / HealthTech
> **Category:** Software
> **Current Version:** Interactive HTML Prototype

---

## 📌 Problem Statement

Livestock owners and veterinary departments often face challenges in identifying and responding to emerging animal diseases.

* **Late disease reporting:** Farmers may report symptoms only after trying local treatments.
* **Fragmented data:** Farm, veterinary dispensary, laboratory, vaccination, and surveillance records are disconnected.
* **Incomplete health records:** Animal vaccination and treatment histories may be missing.
* **Limited connectivity:** Rural villages may have unreliable internet access.
* **Delayed outbreak detection:** Disease clusters may not be identified quickly through manual reporting.
* **Laboratory coordination gaps:** Sample collection, referral, tracking, and result reporting can be disconnected.
* **Language barriers:** Farmers may struggle to use digital tools that are not available in their preferred language.
* **Zoonotic risks:** Diseases that can spread between animals and humans require timely detection and coordination.

## 💡 Our Solution

PashuSetu proposes a unified, **One Health, offline-first Early Warning System** for livestock disease surveillance.

The platform is designed around the following workflow:

**Report → Triage → Detect → Map → Alert → Refer → Contain**

It aims to support early symptom reporting, risk assessment, geospatial outbreak monitoring, veterinary verification, laboratory referrals, vaccination planning, and coordinated response.

## ✨ Key Features

### 📊 1. Livestock Health Dashboard

* Key performance indicators for reports, suspected outbreaks, vaccination coverage, and laboratory samples.
* Overview of potential disease activity.
* Visual summaries for veterinary decision-making.

### 🗺️ 2. Geospatial Village Risk Map

* Interactive village markers with different risk levels.
* Village-level symptom and case summaries.
* Block filtering for focused monitoring.
* Visual risk zones and map overlays for potential containment planning.

### 🚨 3. Live Alert Feed

* View suspected disease alerts.
* Review reported symptoms and affected animal groups.
* Access outbreak response plans.
* Simulate alert verification and status updates.

### 📈 4. Disease Trend Monitoring

* Weekly report trend visualization.
* Alert-threshold indicators for identifying potential spikes.
* Vaccination coverage comparisons across blocks.
* Illustrative risk forecasts for the next 30 days.

### 💉 5. Vaccination Coverage Monitoring

* Compare vaccination coverage across administrative blocks.
* Highlight areas with lower coverage.
* Support planning for targeted vaccination drives and ring vaccination.

### 🧪 6. Laboratory Referral Workflow

* Visualize sample progress through collection, transit, laboratory processing, and result reporting.
* Demonstrate the proposed lab referral loop.
* Include QR-based sample tracking in the broader solution roadmap.

### 📱 7. Farmer Report Simulation

* Simulate a farmer reporting animal symptoms.
* Demonstrate report confirmation and triage.
* Test online and offline interface states.

### 📡 8. Offline Queue Demonstration

* Switch between online and offline modes.
* Queue simulated farmer reports while offline.
* Demonstrate syncing queued reports when returning online.

**Note:** Offline storage and synchronization in the current prototype are simulated in the interface. Persistent local storage and real network synchronization require further implementation.

### 🌐 9. Accessible Interface

* Responsive dashboard layout.
* Light and dark theme support.
* Interactive controls and village selection.
* English and Hindi advisory previews.

---

## 🧠 Core Innovation and USP

PashuSetu is designed around several key concepts:

* **Offline-first:** Support reporting in low-connectivity areas, with synchronization when connectivity returns.
* **Multilingual and voice-first:** Proposed access through local languages, voice input, and IVR.
* **Syndromic surveillance:** Identify potentially concerning patterns from reported symptoms.
* **Edge AI:** Planned lightweight on-device triage capabilities.
* **Human-in-the-loop:** Veterinary professionals verify alerts before confirmed outbreak decisions.
* **Pashu Aadhaar integration:** Proposed linkage with animal-level digital health records.
* **QR sample tracking:** A proposed traceable link between sample collection and laboratory results.
* **Containment protocol:** Support quarantine advisories, movement restrictions, and ring vaccination planning.
* **Zoonotic alert bridge:** Proposed coordination with public health surveillance systems.
* **Interoperability:** Planned integration with relevant livestock and disease surveillance systems.

These are intended solution capabilities; external integrations and AI-based functions are not all implemented in the current HTML prototype.

## 🔄 Proposed System Workflow

1. A farmer reports animal symptoms through a supported reporting channel.
2. A triage system assigns an initial risk category.
3. The report receives a timestamp and location when available.
4. Disease surveillance analytics identify unusual clusters of symptoms or cases.
5. A veterinary officer reviews and verifies the suspected alert.
6. A sample is referred to a laboratory when required.
7. Relevant containment measures and local advisories are coordinated.
8. The dashboard reflects updated case statuses and response progress.

## 🛠️ Technology Stack

### Current Prototype

* **HTML5** — Page structure
* **CSS3** — Responsive layout, neumorphic styling, themes, and animations
* **Vanilla JavaScript** — Interactive dashboard, simulated reports, filters, charts, and interface state
* **Google Fonts** — Fredoka and Nunito
* **SVG** — Interactive map and data visualizations

### Proposed Future Stack

| Component                | Proposed Technology                      |
| ------------------------ | ---------------------------------------- |
| Frontend                 | React or Flutter / Progressive Web App   |
| Backend                  | FastAPI or Node.js                       |
| Database                 | PostgreSQL + PostGIS                     |
| Offline storage          | IndexedDB or SQLite                      |
| AI and analytics         | Python, scikit-learn, TensorFlow Lite    |
| Voice and language       | Bhashini integration                     |
| Geospatial visualization | Leaflet, QGIS                            |
| Messaging                | SMS, IVR, WhatsApp Business API          |
| Deployment               | Docker and suitable cloud infrastructure |

*The proposed stack may evolve during development.*

## 🚀 Getting Started

You can run the current prototype locally without installing additional JavaScript packages.

### Prerequisites

* A modern web browser such as Chrome, Edge, or Firefox.
* Git, if you want to clone the repository.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Debashissss/PashuSetu.git
```

**2. Navigate to the project directory**

```bash
cd PashuSetu
```

**3. Open the HTML prototype**

Open `PashuSetu Command Centre (prototype).html` in your web browser.

Alternatively, open the project folder in VS Code and use the Live Server extension.

No backend server or package installation is required for the current standalone prototype.

## 🖥️ Dashboard Modules

| Module               | Purpose                                     |
| -------------------- | ------------------------------------------- |
| KPI Cards            | Summarize livestock health indicators       |
| Village Risk Map     | Visualize simulated village-level risk      |
| Live Alerts          | Review suspected disease reports            |
| Weekly Trends        | Demonstrate report-spike monitoring         |
| Vaccination Coverage | Compare block-level coverage                |
| Risk Forecast        | Display illustrative future risk categories |
| Lab Referral Loop    | Visualize sample workflow                   |
| Reporting Channels   | Illustrate how reports may arrive           |
| Offline Queue        | Demonstrate simulated offline reporting     |

## 🧪 Demo Data Disclaimer

**This repository currently contains an interactive prototype with simulated data.**

* Village names, animal counts, disease alerts, confidence scores, and vaccination percentages are illustrative.
* Dashboard totals and trend charts are demonstration values.
* The displayed risk forecast is not a validated predictive model.
* Disease classifications are not medical or veterinary diagnoses.
* Online/offline behavior and laboratory actions are simulated rather than connected to live services.

The prototype is intended for demonstration, interface evaluation, and further development—not for real-world outbreak management or veterinary decision-making.

## 🛣️ Roadmap

* [ ] Develop a persistent backend and database.
* [ ] Implement secure farmer and veterinary user authentication.
* [ ] Build real offline data storage and automatic synchronization.
* [ ] Add multilingual voice reporting and IVR integration.
* [ ] Develop and validate symptom-based triage.
* [ ] Implement geospatial disease-cluster detection.
* [ ] Integrate animal-level vaccination and treatment records.
* [ ] Add QR-based laboratory sample tracking.
* [ ] Implement real-time notifications and veterinary task assignment.
* [ ] Evaluate predictive models using validated disease surveillance data.
* [ ] Integrate with relevant government livestock and public health systems.
* [ ] Conduct a controlled pilot with veterinary professionals and participating villages.

## 🌍 Expected Impact

* Earlier reporting of suspected livestock diseases.
* Faster identification of potentially emerging outbreaks.
* Improved access to veterinary services in low-connectivity regions.
* Better vaccination planning and follow-up.
* More coordinated laboratory referrals and response activities.
* Improved awareness of zoonotic disease risks.
* Stronger data-driven livestock health surveillance.

Actual impact will need to be measured through pilot deployment and field validation.

## 🔐 Privacy and Responsible Use

The planned production platform should incorporate:

* Consent-based data collection.
* Role-based access controls.
* Secure transmission and storage.
* Protection of farmers' and animal owners' personal information.
* Appropriate anonymization of aggregated surveillance data.
* Human veterinary review of high-risk alerts.
* Alignment with applicable data protection requirements, including the Digital Personal Data Protection Act, 2023, where applicable.

## 🔗 Repository

**GitHub:** https://github.com/Debashissss/PashuSetu

## 👥 Team

**Project:** PashuSetu
**Event:** Smart India Hackathon 2026
**Team Name:** Add your official team name here.
**Team Members:** Add your team members and roles here.

## 📚 References and Further Reading

* Department of Animal Husbandry and Dairying (DAHD) — livestock development and digital livestock initiatives.
* ICAR-NIVEDI — National Animal Disease Referral Expert System (NADRES).
* National Animal Disease Control Programme (NADCP).
* World Organisation for Animal Health (WOAH) — World Animal Health Information System (WAHIS).
* World Health Organization (WHO) — One Health resources.
* National Centre for Disease Control (NCDC) — Integrated Disease Surveillance Programme (IDSP).

*Add verified official reference URLs before the final project submission.*

---

**PashuSetu — Connecting Farmers, Veterinary Services, Laboratories, and Public Health for a Healthier Livestock Future.** 🐄🌱
