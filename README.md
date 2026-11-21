# 🏙️ CivicLens — AI-Powered Municipal Complaint Management System

**Turning citizen complaints into actionable civic solutions.**

CivicLens is a smart municipal complaint management platform designed to simplify how citizens report civic problems and how municipal authorities manage and resolve them.

The platform streamlines complaint registration, categorization, severity assessment, department assignment, duplicate detection, and resolution tracking through a centralized interface.

It aims to make urban governance more transparent, responsive, and efficient.

---

## 🌟 Key Features

### 👤 1. Citizen Portal
- Secure sign-in for citizens.
- Submit civic complaints with descriptions and optional photographs.
- Select ward and provide location details.
- Voice-based complaint input.
- Multilingual complaint support.

### 🤖 2. Intelligent Complaint Triage
- Automatic complaint categorization.
- Rule-based severity assessment.
- Four priority levels:
  - 🔴 Critical
  - 🟠 High
  - 🟡 Medium
  - 🟢 Low
- Transparent one-line explanation for severity assignment.
- Automatic department routing.

### 🔄 3. Duplicate Complaint Detection
- Identifies similar complaints within the same ward.
- Groups repeated reports under existing incidents.
- Tracks duplicate endorsements.
- Helps minimize redundant complaint handling.

### 🏛️ 4. Municipal Admin Dashboard
- Centralized complaint management.
- View and manage citizen grievances.
- Update complaint status.
- Monitor departmental workload.
- Track severity distribution.
- View high-priority complaints.
- Monitor SLA performance.
- Activity log and simulated live complaint feed.

### 📊 5. Complaint Tracking
- Unique complaint ticket IDs.
- Complaint status monitoring.
- Resolution priority and target timelines.
- Simulated WhatsApp acknowledgement receipts.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive UI and styling |
| JavaScript | Application logic and interactions |
| LocalStorage | Browser-side data persistence |
| Web Speech API | Voice input (browser support required) |
| SVG | Icons and dashboard visualizations |

**External Resources:**
- Google Fonts — Typography
- Unsplash — Sample demonstration images

---

## 🏗️ Application Architecture

The current prototype follows a client-side architecture.

```text
             CivicLens
                 |
        -------------------
        |                 |
    Citizen Portal    Admin Portal
        |                 |
        ---------+---------
                 |
        Complaint Processing
                 |
        -------------------
        |        |        |
   Category  Severity  Duplicate
   Detection Assessment Detection
        |        |        |
        -------------------
                 |
        Department Routing
                 |
        -------------------
        |                 |
   Complaint Queue   Admin Dashboard
        |                 |
        -------------------
                 |
       Browser LocalStorage
```

---

## 🏢 Supported Complaint Categories

CivicLens supports six major municipal departments:

1. **Roads & Infrastructure** — Potholes, damaged roads and flyover issues.
2. **Electricity** — Broken wires, electrical hazards and streetlights.
3. **Water Supply** — Pipeline leakage and water supply problems.
4. **Solid Waste Management** — Garbage accumulation and sanitation.
5. **Drainage & Flood Control** — Blocked drains, open manholes and flooding.
6. **Urban Forestry** — Fallen trees and hazardous branches.

---

## 🚀 Getting Started

Follow these steps to run CivicLens locally.

### Prerequisites

- A modern web browser (Google Chrome recommended).
- Visual Studio Code (optional).
- Live Server extension (optional).

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/CivicLens.git
```

**2. Navigate to the project directory**

```bash
cd CivicLens
```

**3. Open the application**

Open `civiclens_app.html` in your browser.

Alternatively, use the VS Code Live Server extension to launch the application.

No backend installation or package dependencies are required for the current prototype.

---

## 🔐 Demo Credentials

Use the following credentials to explore both application roles.

### Citizen Account

```text
Email: citizen@demo.in
Password: Citizen@123
```

### Administrator Account

```text
Email: admin@civiclens.gov
Password: Admin@123
```

The application also includes predefined complaint scenarios for quick demonstrations.

---

## 📌 Current Implementation Notes

- The current version is a front-end prototype.
- Complaint categorization and severity assessment use JavaScript-based rules.
- Data is stored in browser LocalStorage.
- Authentication is demonstration-level and is not suitable for production security.
- WhatsApp notifications are simulated within the application.
- The live complaint feed is simulated.
- No external municipal department APIs are currently integrated.

A production deployment would require a secure backend, database, real AI/ML services, and authenticated notification integrations.

---

## 🔮 Future Enhancements

- Integration of a trained NLP model for intelligent complaint classification.
- Real-time multilingual translation.
- Computer Vision for identifying civic issues from uploaded images.
- GPS-based complaint location detection.
- Backend integration using Java Spring Boot or FastAPI.
- PostgreSQL database integration.
- Real WhatsApp Business API notifications.
- Real-time municipal department integration.
- Mobile application for citizens.
- Advanced analytics and predictive maintenance.

---

## 🌍 Social Impact

CivicLens aims to bridge the communication gap between citizens and municipal authorities.

By prioritizing urgent civic problems, reducing duplicate reports, and improving complaint visibility, the platform has the potential to contribute to safer neighbourhoods and more accountable urban governance.

**Our Vision: Smarter Cities. Faster Responses. Better Communities.**

---

## 👨‍💻 Project Information

**Project Name:** CivicLens  
**Domain:** Artificial Intelligence / Smart Governance  
**Project Type:** Web Application  
**Developed For:** College Prompt-to-Product Event

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with ❤️ to make our cities better.**
