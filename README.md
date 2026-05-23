# Expense Tracker CLI 🪙

A high-performance, crash-proof Command Line Interface (CLI) built with pure Python. This application allows users to track daily finances directly from the terminal, leveraging local JSON persistence to ensure zero data loss across execution lifecycles.

Developed as a showcase of clean Object-Oriented Programming (OOP) principles, defensive exception handling, and robust state serialization.

---

## 🚀 Key Features

* **Volatile & Non-Volatile Synchronization:** Automated state management that checks for data files on boot and synchronizes in-memory tracking arrays with local JSON disk storage instantly upon data modification.
* **Defensive Input Validation:** Built-in error catching wraps all terminal inputs, ensuring invalid dates, malformed float values, or out-of-bounds array indices trigger graceful alerts rather than runtime application crashes.
* **Immersive Terminal UI Control:** Implements automated platform-aware system clearing commands (`cls` vs `clear`) alongside timed state pauses to present a highly responsive, clean console experience.

---

## 🛠️ Technical Stack & Architecture

* **Language:** Python 3.13+
* **Data Storage:** Structured JSON Database (`expenses.json`)
* **Core Modules:** `datetime` (temporal validation), `json` (data serialization), `os` (file-system pathing & terminal execution control).

---

## 💻 Installation & Usage

### Prerequisites
Ensure you have Python installed on your local environment.

### 1. Clone the Repository
```bash
git clone [https://github.com/swenithareddy-tech/expense-tracker-cli.git](https://github.com/swenithareddy-tech/expense-tracker-cli.git)
cd expense-tracker-cli
