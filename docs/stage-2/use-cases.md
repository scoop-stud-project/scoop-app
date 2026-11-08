## System Architecture & Module Descriptions

The SCoop platform organizes domain-specific functionality into four core architectural modules. Common system administration logic (such as user authentication and registration) is handled globally, while these modules focus exclusively on core platform interactions.

---

### 1. Project & Casting Configuration Module
Enables project creators to define and structure their project initiatives without administrative overhead.

* **Project Scope & Goals:** Allows creators to establish the primary context of their initiative (e.g., hackathon sprint, side-project portfolio piece, or startup MVP) and define expected time commitments.
* **Structured Role Slots:** Creators configure explicit role positions (e.g., Backend Developer, UI/UX Designer) with precise technical skill requirements, maximum capacity, and location/workload constraints.

---

### 2. Matchmaking & Discovery Module
Drives personalized candidate and project discovery using a deterministic relational scoring engine.

* **Qualified Discovery:** Provides candidates with filtered browsing of active, open project roles based on their personal profile and availability.
* **Relational Compatibility Engine:** Automatically calculates a 0–100% compatibility score by comparing candidate skills, role preferences, and project goals against open role slot requirements.
* **Candidate Pool Filtering:** Allows project creators to filter, rank, and search qualified student profiles to discover matching talent.

---

### 3. Recruitment & Team Formation Module
Coordinates the end-to-end recruitment lifecycle from application to final team lock-in.

* **Application & Invitation Pipeline:** Manages bidirectional recruitment transactions, allowing students to submit pending applications for role slots and creators to issue direct invitations.
* **Candidate Evaluation & Assignment:** Facilitates applicant review and slot confirmation, binding confirmed students to specific role assignments.
* **Automated Team Lock-In:** Automatically locks the team, resolves remaining pending requests, and reveals private workspace communication links (e.g., Discord, GitHub) once all defined role slots are filled.

---

### 4. Peer Review & Reliability Module
Establishes community trust and accountability following project completion.

* **Post-Project Evaluations:** Enables verified team members to submit performance and collaboration reviews for their teammates upon project completion.
* **Reliability Score Engine:** Automatically processes submitted peer feedback and project completion records to recalculate and update public user reliability scores, promoting transparency and discouraging dropouts.
