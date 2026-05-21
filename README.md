# 🚗 Car Road Tax & EMI Calculator

> **"Where finance meets clarity."**  
> A complete on-road price & EMI calculator built for the Indian automotive market.

![Made with HTML CSS JS](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-f7d569?style=flat-square&labelColor=0f111d)
![Single File](https://img.shields.io/badge/Single%20File-index.html-f7c25a?style=flat-square&labelColor=0f111d)
![India](https://img.shields.io/badge/Market-India%20🇮🇳-f7d569?style=flat-square&labelColor=0f111d)

---

## ✨ Features

- 🧮 **Live EMI Calculation** — results update instantly on every input change, no button needed
- 🗺️ **State-wise Road Tax** — auto-fills road tax % for all 28 states + 8 UTs based on fuel type
- 🚘 **Complete On-Road Breakdown** — Ex-showroom + Road Tax + Registration + TCS + Insurance + Accessories
- 🏦 **Bank Presets** — one-click rate fill for SBI, HDFC, ICICI, Axis, Kotak
- 📅 **Amortization Schedule** — full month-by-month loan breakdown table
- 🥧 **Visual Donut Chart** — principal vs interest vs other charges
- 🌿 **EV Support** — road tax exemption auto-applied for Electric vehicles
- 📱 **Responsive** — works on mobile and desktop
- 🖨️ **Print Ready** — clean print stylesheet included

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | Vanilla CSS (CSS Custom Properties) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Playfair Display + Inter |
| Storage | Stateless — no localStorage needed |
| Dependencies | Zero — no frameworks, no npm |

---

## 📐 How It Works

```
Ex-Showroom Price
  + Road Tax        (auto-filled by state & fuel type)
  + Registration    (default ₹1,500)
  + TCS             (1% for vehicles above ₹10L)
  + Insurance       (default ₹25,000)
  + Accessories     (default ₹5,000)
─────────────────────────────────────────
  = Total On-Road Price

  − Down Payment
─────────────────
  = Loan Amount  →  EMI = P × r × (1+r)^n / ((1+r)^n − 1)
```

---

## 🗺️ Road Tax Coverage

Covers all major Indian states and UTs including Delhi, Maharashtra, Karnataka, Tamil Nadu, Kerala, and more — with separate rates for Petrol, Diesel, CNG, and Electric vehicles.

---

## 🚀 Getting Started

No installation needed. Just open the file:

```bash
# Clone the repo
git clone https://github.com/nrashwin04/car-emi-calculator

# Open in browser
open index.html
```

Or use **Live Server** in VS Code for the best experience.

---

## 📁 Project Structure

```
index.html        ← entire app (HTML + CSS + JS in one file)
README.md
```

---

## 👤 Author

**Ashwin Nair**  
[github.com/nrashwin04](https://github.com/nrashwin04)

---
