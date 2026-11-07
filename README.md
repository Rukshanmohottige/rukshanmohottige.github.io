# 🌟 Rukshan Mohottige – Personal Portfolio

A sleek, responsive, and modern personal developer portfolio tailored for **Rukshan Mohottige**.

Featuring real projects based on your GitHub (`https://github.com/Rukshanmohottige`) and LinkedIn background, plus **Direct WhatsApp Message Delivery** for anyone contacting you!

---

## 🚀 Key Highlights & New Updates

### 1. 💬 Instant WhatsApp Messaging System
- **Floating WhatsApp Widget**: Persistent pulsing green button in the bottom-left corner with quick access to chat with you directly.
- **Auto-Formatting Contact Form**: When visitors fill out your contact form (Name, Email/Phone, Subject, Message) and click **"Send Message to My WhatsApp"**, it automatically prepares and opens the message directly in their WhatsApp app or WhatsApp Web, formatted as:
  ```text
  👋 Hello Rukshan, I am reaching out from your portfolio!

  👤 Name: [Visitor's Name]
  📧 Email: [Visitor's Email]
  📌 Subject: [Subject]

  💬 Message:
  [Visitor's Message]
  ```
- **How to Update Your Phone Number**:
  Open `script.js` and edit the phone number at the very top (line 10):
  ```javascript
  const WHATSAPP_PHONE_NUMBER = '947XXXXXXXX'; // Put your real WhatsApp number with country code (94 for Sri Lanka, no + or spaces)
  ```
  Also update `94712345678` in `index.html` with your real number.

---

### 2. 🛠️ Real Projects Featured From Your GitHub & Background
1. **Employee Leave Management System**:
   - Automated corporate leave workflow system for employees and managers with leave tracking, approval status, and database management.
   - Stack: Java / Node.js, Express, MySQL, REST API.
2. **Finance Management & Finance Module**:
   - Comprehensive budget and financial ledger module tracking transactions, income/expense analytics, and cash flow visualizations.
   - Stack: Vue.js / React, Node.js, MySQL / DB, Data Visualization.
3. **Smart Medical Hand Band (IoT Healthcare Wearable)**:
   - Wearable healthcare telemetry project monitoring vital signals (heart rate, temperature), abnormal alert detection, and hospital console sync.
   - Stack: IoT Hardware, Embedded C++, Microcontroller Sensors, Telemetry.
4. **Reactive Single-Page Applications (Vue.js 3)**:
   - Component-driven modular web applications built with Vue 3, Vite, and state management.
   - Stack: Vue.js, Vite, JavaScript ES6+, Responsive CSS.
5. **Native Android Applications**:
   - Native Android mobile projects developed with Android Studio, Java/Kotlin, SQLite/Room, and Material Design UI.
   - Stack: Android Studio, Java / Kotlin, SQLite, Material Design.

---

### 3. 🌐 Social & Professional Profiles Integrated
- **GitHub**: [github.com/Rukshanmohottige](https://github.com/Rukshanmohottige)
- **LinkedIn**: [linkedin.com/in/rukshan-mohottige-587150202/](https://www.linkedin.com/in/rukshan-mohottige-587150202/)
- **Instagram**: [instagram.com/ruksha.n__/](https://www.instagram.com/ruksha.n__/)
- **Facebook**: [facebook.com/profile.php?id=100090129785737](https://www.facebook.com/profile.php?id=100090129785737)
- **Email**: `rukshanmohottige@gmail.com`

---

## 💻 How to View & Run Locally

### Option 1: Direct Double Click
Double click [index.html](file:///c:/Users/LapMart.lk/Desktop/porfolio/index.html) to open in your browser!

### Option 2: Run with Node.js
```bash
npm start
```
(or `npx serve .`)

---

## 🌐 1-Click Deployment to GitHub Pages

1. Push your files to your GitHub repository:
   ```bash
   git add .
   git commit -m "Update portfolio with real projects and WhatsApp messaging"
   git push origin main
   ```
2. In GitHub, go to your repository **Settings > Pages > Branch: main / root** and click Save.
3. Your portfolio will be live worldwide!
