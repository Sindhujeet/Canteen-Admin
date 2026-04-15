# 🍔 GUS Canteen - Admin Portal

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Deployment](https://img.shields.io/badge/Deployed_on-Vercel-black)

The **Admin Portal** is the secure, administrative backbone of the GUS Canteen system. Built as a standalone application, it provides the canteen staff with a high-performance dashboard to manage operations in real-time. 

To ensure maximum security, this admin panel is completely decoupled from the student-facing ordering application.

---

## ✨ Key Features
* **Inventory Management:** Full Create, Read, Update, Delete capabilities for menu items.
* **Category Control:** Dynamically add or remove food categories.
* **Live Stock Toggle:** Instantly toggle item availability which reflects immediately for students.
* **Mobile-Responsive Admin:** Manage the canteen from a desktop or a smartphone.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Database:** MongoDB Atlas
* **Backend:** Node.js & Express.js (Hosted on Render)
* **Hosting:** Vercel

---

## 🔒 Security Architecture
This system utilizes a **Decoupled Frontend Architecture**:
1. **Student Frontend:** Public-facing, limited to ordering.
2. **Admin Frontend:** Private, isolated URL containing all management logic.
3. **Shared API:** Both frontends communicate with a centralized Render backend.
4. 
---

##  📂 Project Structure
Canteen-Admin/
├── index.html        # Admin Entry / Login
├── dashboard.html    # Core metrics and navigation
├── menu.html         # Food item management UI
├── inventory.html    # Stock and quantity controls
├── billing.html      # Transaction management
├── data.js           # API integration and Fetch logic
└── style.css         # Shared glassmorphism styling
---

## 🚀 Deployment & Local Setup
**Live Link:** [Insert your secret Vercel URL here]

**To run this project locally on your machine:**
1. Clone the repo: 
   `git clone https://github.com/Sindhujeet/Canteen-Admin.git`
2. Open the folder in VS Code.
3. Launch with the **Live Server** extension or run `python -m http.server 8000`.

---

## 👨‍💻 Developer
**Sindhujeet** *Computer Science Student*

[GitHub Profile](https://github.com/Sindhujeet) | [LinkedIn](https://www.linkedin.com/in/sindhujeet-biswas-548169351?utm_source=share_via&utm_content=profile&utm_medium=member_android)
