# 👛 Pocket Planner Pro

> **Smart financial tracking made simple, secure, and fully customizable.**

Pocket Planner Pro is a feature-rich, single-page personal finance web application designed to help you manage your wealth, monitor daily spending, track investments, and plan for your financial future—all with a sleek, responsive UI and complete local data privacy.

---

## 📸 Preview

![Pocket Planner Dashboard Login Screen]<img width="1366" height="667" alt="Screen Shot 2026-10-12 at 17 54 15-fullpage" src="https://github.com/user-attachments/assets/03f5d562-e08b-4615-a2d1-1c32170370ed" />
<img width="1342" height="938" alt="Screen Shot 2026-10-12 at 18 03 10-fullpage" src="https://github.com/user-attachments/assets/9bf797ea-a974-4f90-8c00-3d5febaebfec" />


---

## ✨ Key Features

* **Secure Authentication**: Local username and 4-digit PIN protection keeping your financial data private.
* **Comprehensive Dashboard**: Real-time overview of total balance, income, expenses, and quick budget tracking.
* **Transaction Management**: Easily add, edit, categorize, and search income and expense records with custom date selection.
* **Interactive Calendar View**: Visual day-by-day breakdown of cash flows, recurring expenses, and active goals.
* **Advanced Analytics**: Clean data visualisations powered by **Chart.js** to monitor spending patterns.
* **Investment Portfolio**: Track stocks, crypto, bonds, real estate, and mutual funds with profit/loss metrics.
* **Savings Goals**: Set target amounts, track progress visually, and contribute funds dynamically.
* **Subscriptions & Monthly EMIs**: Keep tabs on recurring bills, streaming services, and active loan schedules.
* **Bank Accounts**: Manage multiple bank accounts, checking/savings balances, and account-specific ledgers.
* **Customization & Themes**: 
  * Light, Dark, and System theme synchronization.
  * Fully customizable background gradients, color schemes, card tones, and navigation accents.
  * Preset quick themes (Cosmic, Sunset, Ocean, Forest, Cyberpunk, etc.).
* **PDF Reporting**: Export clean summary PDF reports using **jsPDF**

---

## 🛠️ Built With

* **HTML5** & **CSS3** (with CSS Variables & Flexbox/Grid Layouts)
* **JavaScript (ES6+)**
* **Chart.js** (for graphical analytics)
* **jsPDF** & **jsPDF-AutoTable** (for PDF report generation)
* **Font Awesome 6.5.1** (for icons)
* **Google Fonts (Inter)**
* **Dicebear API** (for dynamic avatar generation)

---

## 🚀 Getting Started

Since this is a lightweight, client-side web application built with vanilla web technologies, you don't need any complex build steps or backend server setups to run it!

### Prerequisites
All you need is a modern web browser (Chrome, Firefox, Edge, or Safari).

### Installation & Running Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/pocket-planner-pro.git](https://github.com/your-username/pocket-planner-pro.git)
Navigate to the project directory:
    Bash

    cd pocket-planner-pro

    Open index.html:
    Double-click index.html or open it directly in your favorite web browser. Alternatively, you can run it via a local development server (like Live Server in VS Code).

📁 Repository Structure

    index.html — Main application file containing the full frontend layout, styling, and application logic

    old index.html — Legacy version archive.

    testing.html — Experimental playground for new features and UI component tests.

🔒 Privacy & Data Storage

Pocket Planner Pro stores all your personal financial data securely inside your browser's localStorage (pp_pro_data). Your financial records never leave your device unless you choose to export them.
