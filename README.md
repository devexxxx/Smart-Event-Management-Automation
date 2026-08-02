# 🎓 Smart Event Management Automation

An end-to-end event management and certificate distribution system built using **n8n** and **Google Workspace**. The project automates participant registration, QR code generation, attendance tracking, personalized certificate creation, PDF generation, cloud storage, and email delivery.

---

## 📌 Features

- 📝 Participant Registration Automation
- 🔳 Automatic QR Code Generation
- ✅ Attendance Verification
- 📄 Personalized Certificate Generation
- 📑 PDF Export using Google Slides
- ☁️ Google Drive Upload & Sharing
- 📧 Automated Email Delivery
- 📊 Google Sheets Database Integration
- ⚠️ Error Handling & Logging

---

## 🏗️ System Architecture

![Overall System Architecture](screenshots/overall-system-architecture.png)

---

## 🔄 Workflow Interaction

![Workflow Interaction](screenshots/workflow-interaction-diagram.png)

---

## ⚡ Event Flow

![Event Flow](screenshots/event-flow.png)

---

# 🛠️ Workflows

## Workflow 1 — Participant Registration

Automates participant registration by generating a unique Participant ID and storing participant details in Google Sheets.

**Screenshot**

![Workflow 1](screenshots/workflow-1-registration.png)

---

## Workflow 2 — QR Code Generation

Generates a unique QR code for every participant and stores it for attendance verification.

**Screenshot**

![Workflow 2](screenshots/workflow-2-qr-generation.png)

---

## Workflow 3 — Attendance Tracking

Marks participant attendance after QR code verification and updates the attendance database.

**Screenshot**

![Workflow 3](screenshots/workflow-3-attendance-tracking.png)

---

## Workflow 4 — Certificate Distribution

Automatically:

- Copies the certificate template
- Replaces placeholders
- Generates PDF
- Uploads to Google Drive
- Creates a shareable link
- Updates Google Sheets
- Sends the certificate via Gmail

**Architecture**

![Certificate Distribution](screenshots/certificate-distribution-architecture.png)

**Workflow**

![Workflow 4](screenshots/workflow-4-certificate-distribution.png)

---

# 📷 Project Screenshots

## Registration Form

![Registration Form](screenshots/registration-form.png)

---

## Registration Database

![Registration Sheet](screenshots/registration-sheet.png)

---

## QR Code

![QR Code](screenshots/qr-code.jpeg)

---

## Generated Certificate

The repository includes a sample generated certificate.

📄 **certificate.pdf**

---

## Certificate Email

![Email](screenshots/email.png)

---

# 📂 Repository Structure

```text
.
├── docs/
├── screenshots/
├── workflows/
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🚀 Technologies Used

- n8n
- Google Sheets API
- Google Drive API
- Google Slides API
- Gmail API
- Google Forms
- QR Code Generation
- JavaScript

---

# 📁 Workflows

| Workflow | Description |
|-----------|-------------|
| Workflow 1 | Participant Registration |
| Workflow 2 | QR Code Generation |
| Workflow 3 | Attendance Tracking |
| Workflow 4 | Certificate Distribution |

---

# 📄 License

This project is licensed under the MIT License.