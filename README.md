# 💱 Currency Converter

A simple and responsive **Currency Converter Web App** that allows users to convert between world currencies in real-time using live exchange rates from a public API.


---

## 🚀 Features

- 🌍 Supports **20+ major global currencies**
- ⚡ Fetches **real-time exchange rates** via ExchangeRate API
- 🔁 **Instant conversion** as you type
- 🔄 **Swap button** to reverse selected currencies
- 🎨 **Beautiful gradient UI** with responsive design
- ⚠️ Built-in **error handling** (invalid input, API issues)

---

## 🖥️ Preview  


https://github.com/user-attachments/assets/7b0f88b1-5650-42a4-a5bb-e528217fe28f



---

## 📂 Project Structure

```text
currency-converter/
│
├── website.html      # Main HTML page (UI + embedded JS)
├── app.js            # Script for API calls and conversion logic
└── README.md         # Project documentation
```

---

## ⚙️ Technologies Used

- **HTML5** – Structure & layout  
- **CSS3** – Styling & responsive design  
- **JavaScript (ES6)** – Logic, API calls, DOM updates  
- **ExchangeRate API** – Live currency exchange data  

---

## 🧩 How It Works

1. User enters an amount in the input field.  
2. Selects **source** and **target** currencies from dropdowns.  
3. App fetches the latest rate from:

```
https://api.exchangerate-api.com/v4/latest/{FROM_CURRENCY}
```

4. Converted amount is displayed instantly.  
5. User can click the **swap (⇅)** button to reverse currencies.  

---

## 🛠️ How to Run Locally

### 1. Clone the repository:
```bash
git clone https://github.com/NandakishorNaiR/curRenCycOnVeRter...--_--.git
```

### 2. Navigate to the project folder:
```bash
cd currency-converter
```

### 3. Open the web app:
Simply open **website.html** in any browser — no installation required.

---

## 🌐 Live Demo

👉 **View Live App on Render:**  
https://flashcurrencyconverter-powerd-by-knoxy.onrender.com

---

## 📸 Example API Output

```json
{
  "base": "USD",
  "date": "2025-10-06",
  "rates": {
    "EUR": 0.94,
    "INR": 83.10,
    "GBP": 0.82
  }
}
```

---

## 📜 License

This project is licensed under the **MIT License** — free to use and modify.

---

## 👨‍💻 Author

**Nandakishore Nair**  
💬 Built with ❤️ using HTML, CSS, and JavaScript.

