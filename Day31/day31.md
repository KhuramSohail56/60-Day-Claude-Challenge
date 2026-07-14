# 🗼 Day 31: AI Supply Chain Control Tower

## 📝 Project Overview
On Day 31, I engineered the **AI Supply Chain Control Tower**[cite: 1]—a real-time, interactive dispatch simulation sandbox designed to put users in the high-stakes position of a Head of Operations[cite: 1]. Confronted with a rapidly unfolding matrix of global supply chain disruptions[cite: 1], players must triage, negotiate, and execute critical decisions under a strict 3-minute time limit[cite: 1]. The goal is to maximize overall network resilience while balancing tight operational constraints in real time[cite: 1].

---

## 🛠️ Key Technical Features
* **Real-Time Asynchronous Game Engine:** Built entirely with pure Vanilla HTML5, CSS3, and JavaScript[cite: 1]. The system features a custom game loop that ticks down active incident timers and handles asynchronous events concurrently[cite: 1].
* **Dynamic Escalation Spawner:** Programmed a difficulty scaling algorithm where the incident spawn intervals steadily contract as the shift progresses, raising operational complexity over time[cite: 1].
* **Live Telemetry & KPI Matrix:** Features an advanced progress grid updating 7 key operational performance metrics in real time: *Service Level, Customer Satisfaction, Inventory Health, Transport Efficiency, Operating Cost, Revenue Protected,* and *Live Score*[cite: 1].
* **Delayed Consequence Simulator:** Implemented deferred state changes where specific user actions trigger delayed operational impacts ($setTimeout$ pipelines) to simulate the downstream knock-on effects typical in supply chains[cite: 1].
* **Futuristic Cyberpunk Interface:** Styled with a premium neon-glow dark aesthetic, custom glassmorphic cards, sliding entry animations, dynamic alert indicators, and custom performance grading calculations (A+ to D)[cite: 1].

---

## ⚙️ Core Simulated Disruptions
The engine randomly generates and scales priority-based incident cards[cite: 1]:
1. **Port Congestion:** Managing vessel blockades and deciding between premium air freight or local rerouting[cite: 1].
2. **Supplier Slippage:** Activating backup manufacturers or ramping parallel internal lines to prevent factory idle times[cite: 1].
3. **Logistics & Warehousing Failures:** Resolving refrigerated truck breakdowns, inventory count mismatches, and sudden regional stockouts[cite: 1].
4. **Customs & Regulatory Delays:** Balancing expedite clearance fees against wait-out delays at major borders[cite: 1].
5. **Ecosystem & Demand Shocks:** Navigating viral social media demand spikes and regional storm fronts disrupting active lanes[cite: 1].

---

## 💡 Key Supply Chain Learnings
* **The Cost of Decisional Latency:** Learned how delaying or ignoring key supply alerts is mathematically worse than taking a suboptimal proactive action. Postponing decisions allowed underlying crises to compound and trigger severe downstream damage[cite: 1].
* **Priority Triage Optimization:** Mastered how to prioritize and manage simultaneous high-threat bottlenecks under pressure, proving that higher priority events require immediate operational focus to prevent catastrophic service level loss[cite: 1].
* **State-Driven Asynchronous UX:** Deepened frontend engineering skills by building complex, self-cleaning DOM arrays where multiple elements independently animate, transition, update telemetry meters, and vanish without interrupting the main game timeline[cite: 1].
