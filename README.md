# ComplaNet — Advanced University Concern & Lost and Found Management System
[![Framework](https://img.shields.io/badge/Vite-7.1-646CFF?logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Database](https://img.shields.io/badge/Backend-Supabase-3ECF8E?logo=supabase)](https://supabase.com/)
[![Testing](https://img.shields.io/badge/Automated%20Testing-Pytest%20%2B%20Allure-red)](https://docs.pytest.org/)

**ComplaNet** is a state-of-the-art University Concern Management System designed to digitize and optimize the resolution of student and staff grievances. Moving beyond traditional paper-based methods, ComplaNet provides a transparent, secure, and data-driven ecosystem for academic, technical, and administrative concerns, alongside a specialized **Lost & Found** management module.

---

## 📖 Table of Contents
- [Agile Workflow & Sprints](#-agile-workflow--sprints)
- [Core Features](#-core-features)
- [Tech Stack & Justification](#-tech-stack--justification)
- [UML & Design Patterns](#-uml--design-patterns)
- [Testing & Quality Assurance](#-testing--quality-assurance)
- [Installation & Setup](#-installation--setup)
- [Team & Roles](#-team--roles)

---

## 🚀 Agile Workflow & Sprints
The project was executed in three high-impact sprints, following the **Scrum Framework**:

### **Sprint 01: The Complainant Foundation**
*   **Focus:** Launching the user-facing platform.
*   **Key Deliverables:** Student/Staff Authentication, Password Reset, and the core **Complaint Submission Engine** with multi-format file upload support (JPEG, PNG, PDF, MP4, MP3) for evidence.

### **Sprint 02: Admin Governance & Analytics**
*   **Focus:** End-to-end admin control and dashboarding.
*   **Key Deliverables:** Admin Dashboard with **Chart.js**, real-time status updates (Pending → In Progress → Resolved), advanced multi-attribute filtering, and universal search logic.

### **Sprint 03: Lost & Found Integration**
*   **Focus:** Campus asset management and automated matching.
*   **Key Deliverables:** Lost Item reporting for students and a **Found Item Match System** for admins, featuring automated email/web notifications for potential matches.

---

## ✨ Core Features

### 🛡️ Secure Role-Based Access
*   **Students/Staff:** Access to personal dashboards, submission forms, and real-time status tracking.
*   **Admins:** High-level oversight, resolution control, status moderation, and deletion of redundant records.
*   **Security:** Native integration with **Supabase Auth** for encrypted logins and secure password recovery flows.

### 📋 Intelligent Complaint Management
*   **Tailored Forms:** Context-aware inputs for Academic, Technical, Facility, Administrative, and Behavioral complaints.
*   **Transparency:** Real-time visibility into the complaint lifecycle for all stakeholders.
*   **Evidence Handling:** Secure cloud storage for file attachments linked directly to specific complaint IDs.

### 🔍 Discovery & Analytics
*   **Global Search:** Find any complaint instantly by ID, Name, or keywords.
*   **Multi-Attribute Filters:** Segment complaints by Date, Category, or Status to optimize administrative efficiency.
*   **Visual Reports:** Interactive charts representing resolution quotas and common issue trends.

---

## 🛠️ Tech Stack & Justification

| Technology | Purpose | Rationale |
| :--- | :--- | :--- |
| **Vite** | Build Tool | Instant hot-reloading and lightning-fast developer experience. |
| **Tailwind CSS** | UI Framework | Rapid, utility-first responsive styling and native Dark Mode support. |
| **JavaScript** | Logic | Async API handling (Supabase) and complex client-side validations. |
| **Supabase** | Backend | Hosted PostgreSQL, Real-time Auth, and S3-compatible Storage. |
| **Pytest** | Testing | Robust automated functional testing with detailed Allure reporting. |

---

## 📐 UML & Design Patterns
ComplaNet is built on a foundation of rigorous software engineering models documented in our PM files:
*   **Use Case Diagrams:** Defining High-Level system interactions for Students, Staff, and Admins.
*   **Activity Diagrams:** Modeling the state transitions (e.g., successful submission vs. validation error).
*   **Sequence Diagrams:** Mapping the chronological data flow between the User, UI, and Supabase Backend.

---

## 🧪 Testing & Quality Assurance
We maintain a strict "Definition of Done" that requires every feature to pass:
*   **Requirement Based Testing:** Validating every User Story against pre-defined acceptance criteria.
*   **Automated Testing:** Python-based **Pytest** scripts for regression testing across all modules.
*   **Performance Audits:** **Google Lighthouse** targets of 90+ for Accessibility, SEO, and Best Practices.
*   **Usability Testing:** Cross-device verification to ensure accessibility on Mobile, Tablet, and Desktop.

---

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shaWD18/CC-sprint1code.git
2. **Setup Dependencies:**
   ```bash
   npm install
3. **Configure Backend:**
Create a .env file with your Supabase credentials:
   ```bash
   VITE_SUPABASE_URL=your_project_url
   VITE_SUPABASE_ANON_KEY=your_anon_key
   ```
4. **Development Mode:**
   ```bash
   npm run dev
   ```
5. **Run Automated Tests:**
   ```bash
   pytest --alluredir=reports
   ```

### 👥 Team & Roles

* **Fathima Salma Muzammil (CB009970):** Scrum Master (Sprint 1), Quality Assurance Analyst (Sprint 2), Business Analyst & Developer (Sprint 3)

* **Mohideen Jiffry Fathima Shahany (CB013281):** Business Analyst & Developer (Sprint 1), Scrum Master (Sprint 2), Quality Assurance Analyst (Sprint 3)

* **Kodikara Arachchige Vidma Jayani (CB013174):**   Quality Assurance Analyst (Sprint 1), Business Analyst & Developer (Sprint 2), Scrum Master Sprint 3)

### 🧑🏻‍💻 Developed for Staffordshire University | COMP50001: Commercial Computing II
