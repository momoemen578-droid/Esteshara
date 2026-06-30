# ⚖️ Esteshara | استشارة

> **A trusted digital legal platform** connecting Egyptian lawyers and clients — securely, transparently, and in full compliance with Egyptian law.

---

### 📝 About

Esteshara is a dual-sided Egyptian LegalTech platform built for two equally important users: the **Lawyer (المحامي)** and the **Client (الموكل)**. The platform digitizes the entire legal engagement journey — from first contact and contract signing, through case execution, all the way to judgment enforcement — while keeping every step legally binding under Egyptian law *(Egyptian Lawyers Law, the Electronic Signature Law, and the Anti-Cybercrime Law)*.

Esteshara is not built to replace the lawyer. It's built to give the Egyptian lawyer faster, more accurate, and more secure tools — while giving the client visibility and trust they've never had before in a traditional legal relationship.

---

### 🚨 Problem Statement

Legal services in Egypt — for both lawyers and clients — suffer from recurring, structural problems:

* **No financial trust mechanism:** clients pay upfront with no guarantee of service; lawyers complete work with no guarantee of payment.
* **No visibility into who actually handles a case:** junior lawyers often draft documents with no transparent review process before they reach the client.
* **Lawyers legally cannot advertise:** leaving newer or smaller-practice lawyers with limited ways to build trust and visibility.
* **Manual, paper-based processes:** physical signatures, in-person Power of Attorney submission slow down cases for clients and lawyers in different cities.
* **No automated conflict-of-interest checks:** risking breaches of client confidentiality.
* **Missed legal deadlines:** due to manual tracking of court dates and procedural windows.
* **Digital evidence with no forensic credibility:** screenshots and chat logs can be edited with no way to verify authenticity in court.
* **Judgment execution is opaque:** winning a case doesn't mean a client easily knows where enforcement currently stands.
* **Recurring financial obligations:** like alimony or installments rely on manual reminders and follow-up.
* **Small disputes escalate:** into multi-year court cases that could often be resolved through fair, fast mediation.
* **Contract drafting relies on outdated templates:** pulled from the internet, risking non-compliance with the latest legal amendments.

> ✨ *Esteshara directly addresses each of these problems with a dedicated feature, detailed below.*

---

### 🎯 Target Users

Esteshara serves two primary user types with equal priority:

#### 👨‍⚖️ The Lawyer (المحامي)
A licensed Egyptian lawyer (senior or junior, solo practitioner or part of a firm) who needs faster case management, secure payment handling, supervision tools for junior staff, and AI-assisted drafting and research.

#### 🧑‍💼 The Client (الموكل)
An individual or business seeking legal representation who needs transparency into their case status, confidence their payment is protected, visibility into who is handling their documents, and trust that their legal process is moving forward correctly.

_Every core feature below was designed with both sides of this relationship in mind — the lawyer's workflow and the client's visibility into that workflow._

---



### ♿ Accessibility Considerations & Known Limitations

We are fully aware that a significant portion of Egypt's population — particularly older or less tech-literate clients — cannot and will not interact with a mobile app directly. This is not a blind spot in the design; it is a deliberately acknowledged boundary.

#### ❓ Why this doesn't undermine the platform
Esteshara's adoption model is **lawyer-first, not client-first**. The lawyer is always the primary point of entry. A client who cannot use a smartphone does not need to — they continue interacting with their lawyer exactly as they always have (in person, by phone). The lawyer uses the platform tools on their end, and the client receives the benefit indirectly:

* **Document Handling:** The lawyer uploads documents on the client's behalf.
* **Financial Protection:** The escrow system protects the client's money without requiring the client to touch the app.
* **Case Tracking:** Judgment execution tracking is managed by the lawyer and shared with the client verbally or in person.
* **SMS Notifications:** For simple status updates, the platform can notify clients via SMS — requiring no app install, no account, no technical literacy.

#### 👥 Who the client-side UI is actually built for
The client-facing interface is designed for a specific, realistic segment:

| Client Type | Can Use the App? | How They Benefit |
| :--- | :---: | :--- |
| **Business owners & companies** *(e.g. Karim Fawry)* | 🟢 **Yes — directly** | Full platform access: contracts, payments, case tracking |
| **Young or mid-age individuals** comfortable with smartphones | 🟢 **Yes — directly** | Case visibility, digital signing, payment protection |
| **Less tech-literate individuals** *(older clients, rural users)* | ❌ **Not directly** | Benefit indirectly via the lawyer as intermediary |
| **Fully illiterate clients** | ❌ **Not directly** | Lawyer acts as full proxy; client benefits from escrow and process integrity without touching the app |

> 🏛️ **The Honest Answer:**
> No LegalTech platform — in Egypt or globally — has solved the digital literacy gap for fully offline users through a mobile app. Attempts to fake this solution produce bad UX for everyone. Our answer is to not pretend the app serves everyone equally, but to design the lawyer-side tools so well that even a client who never opens the app still benefits from a more secure, more transparent, and more accountable legal process than they had before.

---


### ⚡ Key Features

| # | Feature | What It Solves |
| :-: | :--- | :--- |
| **1** | **Escrow Payment System** | Client funds are held securely on the platform and only released to the lawyer once the agreed legal service is completed — protecting both parties financially. |
| **2** | **Sub-Accounts & Supervision** | Senior lawyers manage junior lawyers under their account. Junior-drafted documents require senior approval before reaching the client, with full visibility for the client into the review status. |
| **3** | **Legal Blog & Articles** | A legally compliant alternative to advertising — lawyers publish educational legal content to build trust and visibility without violating Egyptian advertising restrictions for the legal profession. |
| **4** | **Digital Signature** | Contracts can be signed electronically from anywhere, holding full legal validity equal to handwritten signatures under Egyptian law. |
| **5** | **Official Power of Attorney Integration** | Clients can link their official notarized Power of Attorney (التوكيل الرسمي) either via automatic integration with Egypt's national digital platform (مصر الرقمية) or manual upload — required before a lawyer can legally represent them in court. |
| **6** | **Conflict of Interest Check** | Before accepting a new case, the system automatically cross-checks past clients to flag any potential conflict of interest, protecting client confidentiality and lawyer compliance. |
| **7** | **Smart Legal Agenda** | Automatically calculates legal deadlines, sends proactive reminders, and accounts for travel time to court — preventing missed procedural windows. |
| **8** | **Legal Digital Timestamping** | Generates a unique cryptographic hash and immutable timestamp for uploaded evidence, giving digital documents and chat logs court-admissible authenticity under Egyptian Anti-Cybercrime Law (Article 18). |
| **9** | **Bailiff & Judgment Execution Tracker** | Tracks every step of judgment enforcement in real time — from issuing the executive copy, to bailiff assignment, to final collection — similar to package delivery tracking. |
| **10** | **Smart Contracts & Recurring Payouts** | Automates recurring financial obligations (e.g. monthly alimony or installments), auto-deducting and transferring payments on schedule, with instant alerts and penalty enforcement on missed payments. |
| **11** | **AI-Driven Dispute Resolution (Mediation)** | An AI mediator reviews case documents and proposes a fair settlement; if both parties agree and sign digitally, the settlement gains direct executive legal force. |
| **12** | **AI Contract Builder** | Generates legally compliant contracts based on the latest Egyptian legal amendments, flags risky clauses, and stays continuously updated — always reviewed and approved by the responsible lawyer before use. |

---

### 🤖 AI Case Outcome Predictor

In addition to the 12 core features, Esteshara includes an **AI Case Outcome & Judgment Predictor** that analyzes case evidence, relevant precedents, and the historical tendencies of the specific judicial circuit to estimate the probability of a favorable outcome — giving lawyers a data-backed view before building their legal strategy.

---

### 🔍 Design & Research

#### 📈 Process
1. User Research (Lawyers & Clients)
2. Competitor Analysis (Egyptian & regional LegalTech platforms)
3. Problem Statement Definition
4. SWOT Analysis
5. User Personas (Lawyer Persona & Client Persona)
6. Information Architecture
7. User Flows (dual-sided: Lawyer flow & Client flow)
8. Low-, Mid-, and High-Fidelity Wireframes
9. Visual Identity (Color System, Typography, Component Library)
10. Mobile App UI Design
11. Prototyping & Usability Testing
12. Case Study Documentation

#### 🎨 Visual Identity
* 🏷️ **Primary Background:** `#F5F4F0` (Cream)
* 🏷️ **Primary Brand / Headers:** `#142341` (Deep Navy)
* 🏷️ **Surfaces / Cards:** `#FFFFFF` (White)
* 🟢 **Success / Active States:** `#1D9E75` (Green)
* 🟡 **Pending / Warning States:** `#EF9F27` (Amber)
* 🔴 **Critical / Reject States:** `#E24B4A` (Red)
* 🔤 **Typography:** Cairo *(headings, Arabic-first)*, Plus Jakarta Sans *(body copy)*

#### 🛠️ Tools Used
* **Figma** (UI/UX Design & Prototyping)
* **FigJam** (Research, Flows, IA)
* *(Add any additional tools used — AI tooling, dev stack, etc.)*

---

### 📁 Project Files

* 🗺️ [UX / FigJam File](add_link_here)
* 🎨 [UI / Figma File](add_link_here)
* 📄 [Case Study File](add_link_here)
* 🎬 [Demo Video](add_link_here)

---

### 📱 Screenshots

*(Add mobile screen previews here — Lawyer side and Client side, organized by feature)*

| Lawyer Side | Client Side |
| :---: | :---: |
| ![Lawyer Screenshot](add_image_link_here) | ![Client Screenshot](add_image_link_here) |

---

### 👥 Team Members

| Name | Role | Contribution |
| :--- | :--- | :--- |
| **Name placeholder** | Role placeholder | Primary / Secondary contribution |
| **Name placeholder** | Role placeholder | Primary / Secondary contribution |
| **Name placeholder** | Role placeholder | Primary / Secondary contribution |
| **Name placeholder** | Role placeholder | Primary / Secondary contribution |
| **Name placeholder** | Role placeholder | Primary / Secondary contribution |

---

### 👨‍🏫 Instructor

* **Dr. / Prof.** Name Placeholder

---

### 📄 License

This project is shared for educational and non-commercial purposes. You are free to view and reference the content, but redistribution or commercial use requires permission from the creators.

---

### 🙏 Thanks

**Esteshara Team**
