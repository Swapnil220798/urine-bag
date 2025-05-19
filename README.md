# urine-bag

# Univlabs Smart Urine Bag – Mobile UI

This project is a responsive mobile-first web application for the **Univlabs Smart Urine Bag System**. It provides real-time monitoring, alerts, and a user-friendly interface for patients and caregivers. Built using **HTML**, **TailwindCSS**, and **JavaScript**, this UI simulates core features such as device connection, fill-level visualization, notifications, reports, and patient profile management.

---

## 🧩 Features

### ✅ Multi-Screen Navigation
- **Welcome & Login** – User onboarding.
- **Device Connection** – Simulated BLE device status.
- **Home Screen** – Displays urine bag fill level with dynamic animation.
- **Notifications** – Alert logs including fill thresholds and pressure.
- **Reports** – Historical data on fill rate and alerts.
- **Profile** – Editable patient details.
- **High Alert** – Pulsing emergency screen on overfill/pressure.
- **Q&A & Help** – FAQs and support options.
- **About Us** – Company overview.
- **How-To Video** – Embedded usage tutorial.

---

## 📸 Screens Overview

| Screen        | Description |
|---------------|-------------|
| Welcome       | Entry screen with logo and Get Started button. |
| Login         | Email and password input. Simulates login. |
| Device        | Shows device name and connection status. |
| Home          | Displays urine bag fill level with visual fill animation. |
| Notifications | Logs alerts (e.g., high pressure, 50% full). |
| Reports       | Shows daily stats and allows report download. |
| Profile       | User can edit name, age, gender, condition. |
| High Alert    | Shows emergency alert with pulsing red background. |
| Q&A           | Collapsible FAQ entries and link to help. |
| About Us      | Description and logo of Univlabs. |
| Help          | Contact details and link to tutorial. |
| How to Use    | Embedded video tutorial for device usage. |

---

## 📦 Tech Stack

- **HTML5** – Page structure
- **TailwindCSS** – Utility-first CSS for styling
- **JavaScript (Vanilla)** – Logic for screen switching and simulated dynamic updates

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/univlabs-mobile-ui.git
cd univlabs-mobile-ui
```

### 2. Open the App
You can simply open the `index.html` in any modern browser:

```bash
open index.html
```
_or just double-click the file on your system._

---

## 🔄 Simulated Dynamic Behavior

A JavaScript interval simulates urine bag fill changes every 5 seconds:
- Randomized fill percentage between 0–100%
- UI fill bar animation adjusts accordingly
- If fill level > 80%, auto-triggers the **High Alert** screen

---

## 📁 Assets

Ensure the following assets are present in your project directory:
- `images (1).jpg` – Logo for Welcome screen
- `assets/univlabs-logo.png` – Logo for About Us section
- `assets/tutorial.mp4` – Video tutorial for usage guide

Update image/video paths as needed based on your actual folder structure.

---

## ✅ To-Do / Future Enhancements

- Add BLE communication for real-time device integration
- Store and retrieve user data via backend or local storage
- Enable actual login and authentication
- Generate downloadable PDF reports
- Add user settings and customization options

---

## 📞 Support

For help or inquiries, contact:

- 📧 **Email**: support@univlabs.com  
- ☎️ **Phone**: +1-800-123-4567

---

## 🏷 License

This project is licensed under the [MIT License](LICENSE).
