💱 Currency Converter

A simple and responsive Currency Converter Web App that allows users to convert between different world currencies in real-time using live exchange rates from a public API.

🚀 Features

🌍 Supports 20+ major global currencies

⚡ Fetches real-time exchange rates via ExchangeRate API

🔁 Instant conversion as you type

🔄 Swap button to reverse currency pairs

🎨 Beautiful gradient UI with responsive design

⚠️ Error handling for invalid inputs or failed API requests

🖥️ Preview

📂 Project Structure
├── website.html     # Main HTML file with styling and JS script
├── app.js           # (Optional) Script for fetching data from an external API
└── README.md        # Project documentation

⚙️ Technologies Used

HTML5 – Structure and layout

CSS3 – Responsive design and styling

JavaScript (ES6) – Logic for conversion, API calls, and DOM manipulation

ExchangeRate API – Real-time currency exchange data

🧩 How It Works

The user enters an amount in the input field.

Selects the source and target currencies from dropdown menus.

The app fetches the latest conversion rate from
https://api.exchangerate-api.com/v4/latest/{FROM_CURRENCY}
.

The converted amount and current exchange rate are displayed instantly.

Users can swap the currencies using the swap (⇅) button.

🛠️ How to Run Locally

Clone this repository:

git clone https://github.com/NandakishorNaiR/curRenCycOnVeRter...--_--.git


Navigate to the project folder:

cd currency-converter


Open website.html in your browser.

That’s it! No additional dependencies required.



👉 View Live App on Render https://flashcurrencyconverter-powerd-by-knoxy.onrender.com

📸 Example API Output
{
  "base": "USD",
  "date": "2025-10-06",
  "rates": {
    "EUR": 0.94,
    "INR": 83.10,
    "GBP": 0.82
  }
}

📜 License

This project is licensed under the MIT License — feel free to use and modify it for personal or commercial use.

👨‍💻 Author

Nandakishore NAir

💬 Built with ❤️ using HTML, CSS, and JavaScript.
