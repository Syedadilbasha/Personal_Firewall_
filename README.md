# 🛡️ Personal Firewall

A modern **Personal Firewall Dashboard** built using **HTML, CSS, JavaScript, and Python (Flask)**. This project provides a clean web interface to monitor network activity, manage firewall rules, and maintain security logs. It demonstrates the core concepts of firewall management, network monitoring, and backend API integration.

> **Note:** This project is primarily designed for educational purposes. The current backend simulates firewall operations. Real packet filtering requires integration with operating system firewall APIs (e.g., Windows Firewall or Linux `iptables`).

---

## 📌 Features

* Modern responsive dashboard
* Start and Stop firewall service
* Block and Unblock IP addresses
* Block network ports
* View firewall status
* Export firewall logs
* CSV log storage
* REST API using Flask
* Easy-to-use interface
* Lightweight and beginner-friendly

---

## 🖥️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python 3
* Flask
* Flask-CORS

### Database / Storage

* CSV Log File

---

## 📁 Project Structure

```
Personal-Firewall/
│
├── index.html
├── app.py
├── firewall_logs.csv
├── README.md
├── requirements.txt
│
├── assets/
│
└── screenshots/
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/personal-firewall.git
cd personal-firewall
```

### 2. Install dependencies

```bash
pip install flask flask-cors
```

### 3. Start the backend

```bash
python app.py
```

### 4. Open the frontend

Open `index.html` in your preferred web browser.

---

## 📡 API Endpoints

| Method | Endpoint      | Description        |
| ------ | ------------- | ------------------ |
| GET    | `/status`     | Firewall status    |
| POST   | `/start`      | Start firewall     |
| POST   | `/stop`       | Stop firewall      |
| POST   | `/block_ip`   | Block IP address   |
| POST   | `/unblock_ip` | Unblock IP         |
| POST   | `/block_port` | Block port         |
| GET    | `/logs`       | View firewall logs |

---

## 📊 Dashboard Features

* Firewall Status
* Network Activity Table
* Allowed Connections Counter
* Blocked Connections Counter
* Total Connections Counter
* Firewall Rule Management
* Log Export

---

## 📷 Screenshots

Add screenshots of your dashboard here.

```
screenshots/
├── dashboard.png
├── logs.png
└── firewall-status.png
```

---

## 📄 Log Format

```
Time, Action, Target

2026-06-28 15:30:22, START, Firewall
2026-06-28 15:31:02, BLOCK IP, 192.168.1.10
2026-06-28 15:33:45, BLOCK PORT, 445
```

---

## 🔒 Skills Demonstrated

* Network Security Fundamentals
* Firewall Rule Management
* REST API Development
* Python Programming
* Web Development
* Logging and Monitoring
* Backend Integration
* Cybersecurity Concepts

---

## 🎯 Future Enhancements

* Real Windows Firewall integration
* Linux `iptables` support
* User authentication
* SQLite or MySQL database
* Real-time packet monitoring
* Live traffic graphs
* Email notifications
* Rule scheduling
* Intrusion detection module
* Dark/Light mode switch

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repository and submit pull requests.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Syed Adil**

Cybersecurity Enthusiast | Python Developer | AI & ML Student

GitHub: **https://github.com/Syedadilbasha**

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub.
