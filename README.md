# 💱 Currency Converter

A simple web app that converts currency amounts from one currency to another using a live exchange rate API. It displays flags for selected currencies and updates dynamically.



## 🧰 Technologies Used

- **HTML5** — Webpage structure  
- **CSS3** — Styling the UI  
- **JavaScript (ES6)** — DOM manipulation, API requests, event handling  
- **CurrencyAPI** — For fetching live exchange rates  
- **FlagsAPI** — For displaying country flags by currency  


## 🚀 How to Run

1. Save all files (`index.html`, `styles.css`, `codes.js`, `script.js`) in the same folder.  
2. Replace `API_KEY` in `script.js` with your actual API key from [CurrencyAPI](https://currencyapi.com).  
3. Open `index.html` in your web browser.  
4. Enter the amount, select currencies from the dropdowns, and click **Get Exchange Rate**.  
5. The conversion result and currency flags update automatically.

## 💡 Notes
- Make sure to replace the API key with your own from CurrencyAPI.

- The app uses FlagsAPI to display country flags based on currency codes.

- Error handling is included for failed API requests.

- The dropdowns default to USD (from) and INR (to).



