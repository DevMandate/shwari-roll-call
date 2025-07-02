# 📝 Shwari Roll Call Form

A modern, responsive roll call form for **Shwari Movers & Cleaners**, designed to capture employee attendance and team information accurately and efficiently. This project leverages Google Sheets for backend data storage using Google Apps Script.

---

## 📌 Features

- ✅ Clean, responsive UI using Bootstrap 5
- ✅ Animated UI transitions using AOS (Animate On Scroll)
- ✅ Form submission directly to a linked Google Sheet
- ✅ Input validation with required fields
- ✅ Auto-clear success message after submission
- ✅ Mobile-friendly layout
- ✅ Instant feedback via dynamic success/error messages
- ✅ Prevents multiple form submissions while submitting

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Bootstrap 5, AOS Animation Library
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Backend**: Google Apps Script + Google Sheets API (via Web App URL)

---

## 📂 Project Structure


---

## 📄 Form Fields

The form collects the following employee information:

- Surname
- First Name
- Last Name
- Phone Number
- Location
- ID Number
- Team (Dropdown: Kilimanjaro, Aberdare, Menengai, Radical, Everest, None)
- Role (Dropdown: Coordinator, Team Leader, Driver, Employee)
- Email
- Date Joined

---

## 🔧 How It Works

1. User fills in the form and clicks **Submit**
2. Data is sent to a **Google Apps Script Web App URL**
3. Data is logged into a linked **Google Sheet**
4. Success or error message is shown to the user

---

## ✅ Deployment

This project is deployed using **Google Apps Script**. Deployment instructions:

1. Create a Google Sheet
2. Open `Extensions > Apps Script` in the sheet
3. Paste the Google Apps Script (provided separately)
4. Deploy as a **Web App** with "Anyone" access
5. Update the `scriptURL` in the HTML to your Web App URL
6. Host the form via GitHub Pages, Netlify, or directly in the browser

---

## 📷 Screenshot

![Form Preview](images/shwari%20logo.png)

---

## ✨ Credits

Developed with ❤️ by [DevMandate](https://github.com/DevMandate)  
Design and Concept by **Shwari Movers & Cleaners**

---

## 📃 License

This project is for internal use. Contact the author for reuse or distribution.

