# Expense Tracker (Redux Toolkit)

A simple **Expense Tracker** application built with **React**, **Redux Toolkit**, and **Vite**. The app allows users to add expenses, categorize them, and view a list of all transactions.

🔗 **Live Demo**: [https://delicate-peony-73df92.netlify.app](https://delicate-peony-73df92.netlify.app)

---

## 🚀 Features

* Add expenses with **title**, **amount**, **type (Debit/Credit)**, and **category**
* Global state management using **Redux Toolkit**
* Clean and responsive UI
* Form validation
* Fast development setup using **Vite**

---

## 🛠️ Tech Stack

* **React** (Vite)
* **Redux Toolkit**
* **React Redux**
* **JavaScript (ES6+)**
* **CSS**

---

## 📂 Project Structure

```
Expense-Tracker-Redux
│
├── src
│   ├── Components
│   │   ├── ExpenseForm.jsx
│   │   └── ExpenseList.jsx
│   │
│   ├── features
│   │   └── Expense
│   │       └── expenseSlice.js
│   │
│   ├── Store
│   │   └── store.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   └── App.css
│
├── public
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation & Setup





2. **Navigate to the project directory**

```bash
cd Expense-Tracker-Redux
```

3. **Install dependencies**

```bash
npm install
```

4. **Run the development server**

```bash
npm run dev
```

5. Open your browser and visit:

```
http://localhost:5173
```

---

## 🧠 Redux Logic Overview

* **expenseSlice.js** handles:

  * Adding new expenses
  * Managing expense state

* **store.js** configures the Redux store using `configureStore`

---

## 📸 Screenshots

![Expense Tracker UI](./screenshots/app.png)

---

## 📌 Future Improvements

* Edit and delete expenses
* Persist data using LocalStorage or backend
* Expense summary with charts
* Authentication

---


---

## 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you like this project, give it a star on GitHub!
