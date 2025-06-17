# 💱 Currency Converter App

A simple and interactive **Currency Converter** built with **React**. This app fetches real-time currency exchange rates using an open-source API and helps users convert one currency to another quickly and easily.

---

## 🚀 Features

- 🔄 Real-time currency conversion
- 🌍 Supports multiple currencies
- 💡 Minimal and clean UI
- 📦 Custom React Hook (`useCurrencyInfo`) for API data fetching

---

## 🖼️ Preview

> A sleek UI where users can:
> - Select source and target currencies
> - Input an amount
> - Instantly see converted values

---

## 🧰 Tech Stack

- ⚛️ React (with Hooks)
- 🎣 Custom Hook (`useCurrencyInfo`)
- 🌐 API: [@fawazahmed0/currency-api](https://github.com/fawazahmed0/currency-api)
- 💄 Tailwind CSS (optional — based on usage)

---

## 📂 Project Structure

```
src/
│
├── App.jsx               # Main application logic
├── InputBox.jsx          # Currency input component
└── useCurrencyInfo.js    # Custom hook for fetching currency data
```

---

## 📦 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/currency-converter.git
   cd currency-converter
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the dev server**
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📡 API Info

This app uses a free and fast API from:
```
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/{currency}.json
```
No authentication or API key required!

---

## 🙌 Acknowledgments

- [@fawazahmed0](https://github.com/fawazahmed0) for the public currency API
- React Team for a beautiful developer experience

---

## 🧑‍💻 Author

Built by Yash Kashyap

---


