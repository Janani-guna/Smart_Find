# 🔎 SmartFind – Classroom Lost and Found Management System

SmartFind is a web-based Classroom Lost and Found Management System designed to help students easily report, search, and recover lost items within their classroom or college.

## 📌 Problem Statement

Students often lose items such as ID cards, books, calculators, earphones, water bottles, wallets, and other personal belongings. When someone finds these items, there is no proper platform to connect the item with its owner. Students usually depend on WhatsApp groups, classmates, or verbal communication, which can be difficult and time-consuming.

## 💡 Solution

SmartFind provides a centralized online platform where students can:

- Report lost items
- Report found items
- Search for lost and found items
- Filter items by category and location
- Find possible matches between lost and found items
- Submit claims for their belongings
- Track item status
- Mark items as returned

## ✨ Key Features

- 👤 Student Login and Registration
- 📋 Lost Item Reporting
- 📦 Found Item Reporting
- 🔍 Search and Filter
- 🎯 Smart Item Matching
- 📊 Match Percentage
- ✅ Item Claim System
- 🔔 Notifications
- 📌 Item Status Tracking
- 👨‍🏫 Admin Dashboard
- 📈 Statistics and Analytics
- 📱 Responsive Design

## 🎯 Smart Matching

The system compares details such as:

- Item name
- Category
- Color
- Brand
- Location
- Date
- Description

Based on these details, SmartFind generates a possible match score.

### Example

Lost Item:
> Black Casio Calculator – Classroom 3

Found Item:
> Black Casio Calculator – Classroom 3

Result:
> 🎯 Possible Match – 92%

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- LocalStorage
- JSON
- Chart.js

## 📂 Project Structure

```text
SmartFind/
│
├── index.html
├── login.html
├── register.html
├── dashboard.html
├── report-lost.html
├── report-found.html
├── search.html
├── item-details.html
├── admin.html
│
├── css/
│   ├── style.css
│   ├── dashboard.css
│   └── responsive.css
│
├── js/
│   ├── auth.js
│   ├── storage.js
│   ├── lost.js
│   ├── found.js
│   ├── matching.js
│   ├── search.js
│   ├── claims.js
│   ├── admin.js
│   └── dashboard.js
│
├── assets/
│   └── images/
│
└── data/
    └── sample-data.json
