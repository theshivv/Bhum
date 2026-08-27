<div align="center">
  <img src="https://raw.githubusercontent.com/theshivv/Bhum/main/favicon.ico" alt="Bhum Logo" width="80" height="80" onerror="this.style.display='none'">
  <h1 align="center">
    <span style="color: #05944F;">Bhum</span>
  </h1>
  <p align="center">
    <strong>A Premium Real Estate & Co-Ownership Tracker</strong>
    <br />
    Manage investments, track payments, and visualize profit-shares locally.
  </p>

  <p align="center">
    <a href="https://theshivv.github.io/Bhum"><strong>🟢 Live Demo</strong></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Status-Live-success?style=for-the-badge&logo=github" alt="Status">
    <img src="https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge&logo=google-chrome" alt="Platform">
    <img src="https://img.shields.io/badge/Storage-Local-orange?style=for-the-badge&logo=databricks" alt="Storage">
  </p>
</div>

<br />

## 🌟 Purpose of the Application

**Bhum** is designed to completely demystify real estate co-ownership. When families, friends, or investment syndicates pool money together to buy land or property, tracking exactly who paid what, when they paid it, and how much equity they own becomes incredibly complicated. 

Bhum solves this by providing a unified, sleek, and entirely private dashboard to track property investments, internal transfers, and real-time market valuations without relying on complex spreadsheets. 

---

## ✨ Features

- **🏠 Comprehensive Property Profiles**: Track purchase prices, stamp duty, government fees, and physical dimensions (SqFt / SqM).
- **👥 Intelligent Co-Ownership**: Add multiple owners. Assign shares by **Percentage (%)** or **Fixed Area**.
- **💰 Ledger & Payments**: Log every transaction, from initial token amounts to registry charges. Track exactly which owner contributed what amount via cash or cheque.
- **🔄 Internal Transfers**: Handle scenarios where one co-owner buys out or pays another owner internally.
- **📈 Real-Time Valuation**: Enter the current market rate per SqFt to instantly see your property's appreciation, total profit, and individual owner equity.
- **🔗 Seamless Sharing**: Generate highly compressed, secure shareable links to instantly invite other co-owners to view the exact ledger on their own devices.
- **🔒 100% Private (Local First)**: No backend servers. All your financial data is securely stored exclusively in your browser's Local Storage.

---

## 🎯 Who Can Use This?

- **Real Estate Investors**: Track ROI across a massive portfolio of plots and properties.
- **Families & Friends**: Keep transparent, dispute-free records of joint property purchases.
- **Property Syndicates**: Provide transparent ledger views to all contributing members.
- **Individuals**: Manage personal real estate assets and track installment payments to builders.

---

## 🚀 How to Use It

1. **Visit the App**: Go to [theshivv.github.io/Bhum](https://theshivv.github.io/Bhum).
2. **Add a Property**: Click "+ Add Property" and enter the baseline details (Area, Government Price, etc.).
3. **Add Co-Owners**: Navigate into the property and add the people involved.
4. **Log Tranches (Payments)**: Record the initial token amount, installments, and registry charges. Specify how much each person contributed.
5. **Set the Current Rate**: Update the current market rate (₹/SqFt) to instantly visualize how much your investment has grown and what everyone's exact payout would be if sold today.
6. **Share**: Click the "🔗 Share" button to generate a link and send it to your co-owners so they can import a copy into their own browser.

---

## 💻 Local Setup & Development

Because Bhum is built with modern web standards and requires zero backend servers, running it locally is incredibly fast and simple. 

### Prerequisites
- A modern web browser (Chrome, Safari, Edge, Firefox).
- (Optional) [Node.js](https://nodejs.org/) installed if you want to use a local development server.

### Steps to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/theshivv/Bhum.git
   cd Bhum
   ```

2. **Run it directly**:
   You can simply double-click the `index.html` file to open it directly in your browser. The app will work perfectly since it relies on `localStorage`.

3. **Run with a Local Server (Recommended)**:
   If you want to simulate a real server environment (helpful for testing sharing features or the clipboard API):
   
   Using Node (npx):
   ```bash
   npx serve .
   ```
   *Or using Python:*
   ```bash
   python3 -m http.server 8000
   ```

4. Open your browser and navigate to `http://localhost:3000` (or `8000` depending on your server).

---

<div align="center">
  <i>Built with vanilla HTML, CSS, and JS for ultimate speed and portability.</i>
</div>
