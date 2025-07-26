# 💰 Money Tracker - Expense Manager

A simple, elegant, and interactive personal finance tracker built with pure HTML, CSS, and JavaScript. Track your income, expenses, set monthly budgets, and visualize your financial trends with intuitive charts.

---

## 🧩 Features

- ✅ Add income and expense transactions
- ✅ Set and view your monthly budget
- ✅ View total balance, spent amount, and remaining amount
- ✅ Charts:
  - Income vs Expenses (Pie Chart)
  - Daily Balance Trend (Line Chart)
  - Weekly Net Flow (Bar Chart)
- ✅ Filter transactions: All, This Month, Last Month
- ✅ Local storage support (auto-saves your data in browser)
- ✅ Light, clean UI with responsive layout

---

## 🔒 Data Storage

All data is stored in your **browser's localStorage**, specific to your device.

### 📌 Important:
- ✅ Opening the project on a **new device/browser** will load default sample data.
- ❌ Data does **not sync across devices**.

---

## 🧼 How to Clear Saved Data

To remove all saved entries:
1. Open DevTools → Console
2. Paste and run:
   ```js
   localStorage.removeItem("expenseTrackerData");
   location.reload();
   ```

OR

Add this snippet to the HTML for a visible button:
```html
<button onclick="localStorage.removeItem('expenseTrackerData'); location.reload();">
  Clear All Data
</button>
```

---

## 🛠️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/money-tracker.git
   ```

2. Open `Money_Tracker.html` directly in your browser:
   - No backend or setup required.

---

## 📌 Demo

You can host it using GitHub Pages or open `Money_Tracker.html` locally.

---

## 📝 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
