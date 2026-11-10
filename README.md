# 🩺 Sweety — Blood Glucose Tracker & Doctor Consultation Platform

**An interactive healthcare UI/UX prototype for tracking blood glucose levels and exploring doctor consultation workflows.**

<p align="center">
  <a href="https://chaitanyasivathmika19.github.io/Glucose-tracker-prototype/">
    <strong>🌐 View Live Demo</strong>
  </a>
</p>

## 📌 About the Project

Sweety is a healthcare web prototype designed to help patients record daily blood glucose readings, visualize glucose trends, generate reports, discover doctors, and explore consultation and payment workflows.

The prototype includes separate **Patient and Doctor interfaces**, demonstrating how patients can monitor their readings and how doctors can manage authorized patient records and consultation-related requests.

This project was developed as **Phase 2 — UI/UX Prototyping**, focusing on interface design, navigation, usability, and interactive workflow demonstrations.

## ✨ Features

### 👤 Patient Portal
- **Dashboard:** Overview of daily glucose tracking and consultation activity.
- **Blood Glucose Tracking:** Record readings across four daily slots:
  - Morning (fasting)
  - After breakfast
  - After lunch
  - After dinner
- **Input Validation:** Enforces a glucose range of 40–600 mg/dL and a maximum of four readings per day.
- **Editing Window:** Demonstrates the four-hour reading-editing rule.
- **Calendar:** Navigate dates and review daily tracking completion.
- **Analytics:** Explore glucose statistics and trend visualizations.
- **Reports:** Filter records by date range and export readings as CSV.
- **Doctor Discovery:** Browse sample doctor profiles and consultation plans.
- **Consultation Plans:** Explore pricing, consultation frequency, and two-calendar-month subscription validity.
- **Payment Workflow:** Simulate payment reference submission and pending verification.
- **Messaging:** Explore a sample patient–doctor chat interface.
- **Notifications:** View sample alerts and consultation-related updates.

### 🩺 Doctor Portal
- **Doctor Dashboard:** View sample consultation and patient activity summaries.
- **Patient Records:** Explore the authorized-patient interface.
- **Consultation Requests:** Simulate reviewing consultation requests.
- **Payment Verification:** Demonstrate approval and rejection workflows.
- **Messaging:** Explore the doctor-side chat interface.
- **Notifications:** View sample consultation and payment alerts.
- **Profile:** Access the doctor profile interface.

### 🎨 UI/UX
- Clean, modern healthcare dashboard.
- Teal and lavender color palette.
- Sidebar navigation and dashboard cards.
- Interactive tables, forms, charts, and calendar elements.
- Responsive layout for different screen sizes.
- Patient and Doctor view switching.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, layouts, and responsive design |
| JavaScript | Interactive elements, validation, and demo workflows |
| Git & GitHub | Version control and source code hosting |
| GitHub Pages | Static website deployment |

## 🚀 Live Demo

**[Open the Sweety Prototype](https://chaitanyasivathmika19.github.io/Glucose-tracker-prototype/)**

You can explore the patient and doctor interfaces directly in your browser without installing any software.

## 💻 Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/chaitanyasivathmika19/Glucose-tracker-prototype.git
   ```

2. Open the project folder:

   ```bash
   cd Glucose-tracker-prototype
   ```

3. Open `index.html` in your browser.

No package installation or backend server is required for this prototype.

## 📂 Project Structure

```text
Glucose-tracker-prototype/
├── index.html    # Main prototype with embedded CSS and JavaScript
└── README.md     # Project documentation
```

## ⚠️ Prototype Limitations

This repository represents an **interactive UI/UX prototype**, not a production-ready healthcare application.

- Uses illustrative demo data.
- Interactive workflows are simulated in the browser.
- Does not include production authentication or a backend API.
- Does not persist application records in a database.
- Does not process real payments or verify actual transactions.
- Does not provide real-time doctor communication or server-backed notifications.
- Some analytics and dashboard values are illustrative and should not be interpreted as actual patient data.

A future full-stack implementation may introduce React.js, Node.js, Express.js, and PostgreSQL for persistent data, secure authentication, server-side validation, and authorized access control.

## 🔒 Privacy & Medical Disclaimer

This prototype is intended for educational and demonstration purposes only. It is not a medical device, does not provide a diagnosis, and must not be used to make medical decisions. All displayed health data is illustrative.

## 🎯 Project Objectives

- Design an intuitive blood glucose tracking experience.
- Demonstrate patient and doctor dashboard workflows.
- Explore health analytics and report-generation interfaces.
- Model consultation plans and payment-verification workflows.
- Practice frontend development, interface design, and interactive prototyping.
- Establish a UI/UX foundation for future full-stack development.

## 👩‍💻 Author

**Chaitanya Sivathmika**

- GitHub: [@chaitanyasivathmika19](https://github.com/chaitanyasivathmika19)
- Portfolio: [sivathmika.netlify.app](https://sivathmika.netlify.app/)
- Live Project: [Sweety — Blood Glucose Tracker Prototype](https://chaitanyasivathmika19.github.io/Glucose-tracker-prototype/)

---

*Sweety — Making blood glucose tracking and doctor consultation workflows easier to explore.*
