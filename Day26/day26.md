# 🏥 Day 26: Prior Authorization (PA) Workflow Simulator

## 📝 Project Overview
On Day 26, I designed and developed an interactive **Prior Authorization (PA) Workflow Simulator** tailored for the US Healthcare ecosystem. Prior Authorization is a critical administrative milestone where providers must obtain approval from health insurers before specific medical procedures or therapies can be delivered. This simulator maps out that intricate multi-stakeholder journey in a highly visual, clean, and interactive dashboard.

---

## 🛠️ Key Technical Features
* **Zero-State Initialization:** The dashboard boots into a completely clean state (all lanes empty), waiting for user-initiated data inputs rather than relying on hardcoded records.
* **Dual-Input Mode (Custom Form + Presets):** Features a dedicated configuration panel where users can manually type custom patient data (Name, Age, ICD-10 Diagnosis, Requested Service) or instantly auto-fill realistic pre-configured clinical cases using a dropdown menu.
* **Vanilla JavaScript State Machine:** Manages complex state flow asynchronously across three dedicated operational pillars: **Patient Intake**, **Healthcare Provider Evaluation**, and **Insurance Payer Review**.
* **Micro-Interactions & UX Guards:** Includes custom interactive checklists (Criteria Validation and Document Packet Synthesis) that act as logical gates—ensuring learners understand the exact prerequisites needed before submitting a PA request.
* **Touchpad & Mobile Optimization:** Transitioned from drag-and-drop to a clean click-to-advance pipeline architecture, ensuring full accessibility across laptop touchpads and mobile screens.

---

## ⚙️ Core Clinical Workflows Simulated
1. **Patient Intake:** Logging demographic data, active insurance carriers, and target procedures.
2. **Medical Necessity Validation:** Checking clinical notes to verify if standard criteria (e.g., conservative treatments exhausted, baseline severity met) are fulfilled.
3. **Document Synthesis:** Compiling physical chart notes and signed necessity forms into a secure electronic package.
4. **Payer Gateway Review:** Simulating administrative processing logs, tracking days elapsed, and forcing a terminal status check (Approved vs. Denied).

---

## 💡 Key Operational Learnings
* **US Healthcare Operations & Bottlenecks:** Gained an in-depth understanding of how critical the PA process is. Missing details or failing clinical validations acts as a primary administrative bottleneck, causing massive delays in patient care.
* **State Management Architecture:** Practiced managing complex conditional flows and state trees using pure JavaScript, linking structural DOM elements directly to interactive logical parameters.
* **Interactive Training Design:** Developed skills in translating complex corporate or regulatory workflows into intuitive, gamified dashboard simulators that enhance user engagement and learning retention.

---

## 📸 Interface Preview
*The simulator features a responsive control layout, a linear tracker showing the active phase, multi-lane visualization, a contextual action board, and a real-time system activities logger.*
