# Cosmos Bank 🏦

A desktop banking application built using **Python** and **Tkinter** that simulates real-world banking operations with a clean dark-themed user interface.

---

## 📌 About

**Cosmos Bank** is a simple desktop-based banking system that allows users to perform essential banking operations such as account creation, login, deposits, withdrawals, fund transfers, and transaction tracking.

The application is built entirely using Python's built-in libraries and does not require any external installations.

---

## 📸 Cosmos Bank App Snapshots

<div align="center">

<img width="380" alt="Login Screen" src="https://github.com/user-attachments/assets/7bd6a75e-9416-47c6-b3b6-4bd88692befb" />
&nbsp;&nbsp;
<img width="380" alt="Create Account" src="https://github.com/user-attachments/assets/060cbd70-2604-456a-8ad8-19ccf006c087" />

<br><br>

<img width="380" alt="Account Created" src="https://github.com/user-attachments/assets/1c39c2e8-b754-4226-bb87-253693a1d87b" />
&nbsp;&nbsp;
<img width="380" alt="Dashboard" src="https://github.com/user-attachments/assets/e260773b-408a-497f-9314-e122b17f7b57" />

<br><br>

<img width="380" alt="Transactions" src="https://github.com/user-attachments/assets/5091ed66-26ae-4846-b0b2-d8d2012a4eea" />

</div>

---

## ✨ Features

- 🔐 **Secure Account Creation** — Aadhaar and mobile number validation
- 🔑 **Password Hashing** — SHA-256 encryption for secure login
- 💰 **Deposit & Withdrawal** — Instant balance updates
- 🔄 **Fund Transfer** — Transfer between any two accounts
- 📊 **Real-time Balance Updates** — Reflects after every transaction
- 🧾 **Mini Statement** — Last 5 transactions displayed on dashboard
- 📋 **Copy Account Number** — One-click clipboard copy on registration
- 🌙 **Dark-Themed UI** — Clean and modern interface
- 🔔 **Notification Messages** — Visual feedback for every user action

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Python 3.x** | Core programming language |
| **Tkinter** | GUI framework |
| **Hashlib** | Password hashing |
| **Random** | Account number generation |
| **Datetime** | Transaction timestamps |

> No external libraries required — runs out of the box!

---

## ▶️ How to Run

### Step 1 — Check Python Installation
```bash
python --version
```

### Step 2 — Clone the Repository
```bash
git clone https://github.com/priyag241006/cosmos-bank.git
cd cosmos-bank
```

### Step 3 — Run the Application
```bash
python cosmos_bank.py
```

---

## 📖 How to Use

### 🆕 Create Account
- Click **"Create New Account"**
- Enter required details:
  - Full Name
  - Aadhaar Number (12 digits)
  - Mobile Number (10 digits)
  - Password (minimum 8 characters)
- Click **"Create Account"**
- Save your generated account number

### 🔑 Login
- Enter account number and password
- Click **"Login"**

### 💰 Deposit
- Open **Deposit** tab
- Enter amount and confirm

### 💸 Withdraw
- Open **Withdraw** tab
- Enter amount and confirm

### 🔄 Transfer
- Open **Transfer** tab
- Enter recipient account number and amount
- Confirm transfer

### 🧾 Mini Statement
- Displays last 5 transactions automatically
- 🟢 Credit = Money In
- 🔴 Debit = Money Out

---

## 📁 Project Structure

```
cosmos-bank/
├── cosmos_bank.py      # Main application file
└── README.md           # Project documentation
```

---

## 👩‍💻 Author

**Priya Gundale**
GitHub: [@priyag241006](https://github.com/priyag241006)
