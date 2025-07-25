# 🐣 Young4ChickS

**Young4ChickS** is a youth-led digital poultry distribution system aimed at empowering urban youth (ages 20–30) through sustainable brooding and streamlined chick request management.

---

## 🚀 Project Overview

Young4ChickS was initiated by a Youth Member of Parliament to drive **wealth creation** and **economic engagement** among young urban dwellers. This software solution supports the full cycle of chick distribution — from stock updates by brooder managers, to request approvals, to final sales handling by agents.

It provides tailored interfaces for:

- 🧑‍🌾 Young Farmers (Customers)  
- 🧑‍💼 Brooder Managers  
- 🧾 Sales Agents

Built with **HTML**, **CSS/Bootstrap**, **JavaScript (Node.js)**, and **Pug** templating, the platform offers a smooth, responsive, and user-friendly experience.

---

## 🧑‍🌾 Core Features

### ✅ For Customers (Young Farmers)
- Register with detailed identity verification (NIN, recommender info)
- Submit a chick request every 4 months
- Choose chick type (Layers/Broilers, Local/Exotic)
- Automatically limited by farmer type:
   **Starters**: Max 100 chicks
   **Returning**: Max 500 chicks
- Eligible for 2 bags of feeds (payable after 2 months)
- Track approval status of requests online

### ✅ For Brooder Managers
- Manage stock (quantity, type, age of chicks)
- Approve or reject farmer requests
- Auto-update stock based on approved requests
- View chick distribution records by customer

### ✅ For Sales Agents
- Handle walk-in and phone-based chick requests
- View and manage approved requests from brooder manager
- Complete sales and update final records

## 💼 Business Logic Summary

| Role           | Functionality                                       |
|----------------|-----------------------------------------------------|
| Customer       | Register → Request Chicks → Track Status            |
| Brooder Mgr    | Update Stock → Approve Requests → Reduce Stock      |
| Sales Agent    | Record Requests → Finalize Sale After Approval      |

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Bootstrap 5  
- **Backend**: Node.js  
- **Templating**: Pug  
- **Client-side logic**: JavaScript  
- **Database**: MongoDB (via Mongoose)

## 📝 Validation & Rules

- Only registered youth (ages 20–30) can request chicks  
- Farmer status (Starter/Returning) controls chick quantity  
- Requests are limited to one every 4 months  
- Each approved request comes with optional 2 bags of feed (payable after 2 months)

## 🙌 Acknowledgements
Built with guidance from Refactory Academy, Uganda

## 📌 Getting Started

To run the project locally:

```bash
git clone https://github.com/your-username/young4chicks.git
cd young4chicks
npm install
npm start



Make sure you have Node.js installed.

🙌 Contributing
Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.

📄 License
This project is open-source and free to use for educational and community empowerment purposes.
