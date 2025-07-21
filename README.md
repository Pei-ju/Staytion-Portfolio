# Staytion - Hotel Booking System 飯店訂房系統

A full-stack hotel booking system with **frontend-backend separation**, developed as a team project.  
一個前後端分離的全端訂房系統，由多人協作開發。

The system includes hotel and room management, booking workflows, review moderation, and revenue analytics.  
系統包含飯店與房型管理、訂單流程、評論審核與營收報表功能。

Built with **Java Spring Boot** for backend APIs and **HTML/CSS/JavaScript (Bootstrap)** for the frontend interface.  
後端使用 Java Spring Boot 開發 API，前端使用 HTML、CSS、JavaScript（Bootstrap）設計頁面。

---

## 📁 Project Repositories 專案倉庫

- **Frontend 前端**：[JAVA-Hotel](https://github.com/Pei-ju/JAVA-Hotel)  
   HTML, CSS, JavaScript, and Bootstrap-based UI. Features include an admin dashboard, Chart.js data visualizations, and responsive layout.
   HTML、CSS、JavaScript、Bootstrap 製作的使用者與後台介面，包含 RWD 響應式設計與 Chart.js 圖表視覺化。

- **Backend 後端**：[Staytion](https://github.com/Pei-ju/Staytion)  
  Java Spring Boot + MySQL backend with RESTful APIs for hotels, room types, bookings, reviews, and user accounts.
  使用 Java Spring Boot + MySQL，提供 RESTful API（飯店、房型、訂單、評論、使用者管理等模組）。

---

## 🛠 Tech Stack 技術棧

| Layer 層級    | Technology 技術                              |
|---------------|----------------------------------------------|
| Frontend 前端 | HTML, CSS, JavaScript, Bootstrap             |
| Backend 後端  | Java, Spring Boot, Spring MVC, JPA           |
| Database 資料庫 | MySQL                                       |
| Charts 圖表    | Chart.js                                     |
| Architecture 架構 | RESTful API, 前後端分離                   |
| Tools 工具     | GitHub, Git Branching, Postman, Swagger     |

---

## ✨ Key Features 主要功能

### 🔹 User-Side Booking Platform 使用者端網站

- Browse and search hotels and room types with filters  
  瀏覽與篩選飯店與房型
- View detailed hotel and room information  
  查看詳細設施與圖片資訊
- Book rooms by date and guest number  
  根據日期與人數進行訂房
- Register/login to manage profile and bookings  
  註冊登入後可管理個人資料與訂單
- Review booking history and cancel if needed  
  檢視歷史訂單並可取消未入住訂單
- Responsive design for desktop and mobile  
  響應式設計適配電腦與手機

### 🔸 Admin Dashboard 管理者後台系統

- **Hotel & Room Management 飯店與房型管理**  
  Add, edit, and delete hotels and room types. Control room availability and features.  
  新增、修改、刪除飯店與房型，調整房間數與設施

- **Booking Management 訂單管理**  
  View and filter bookings, update order statuses, and export order data.  
  查詢訂單、更新狀態、匯出報表

- **Review Moderation 評論管理**  
  View and respond to customer reviews. Filter by rating or reply status.  
  篩選與回覆用戶評論、標記回應狀態

- **Analytics & Charts 數據分析與圖表**  
  Visualize monthly revenue, booking trends, and room type distributions using Chart.js (line & pie charts).  
  使用 Chart.js 呈現月營收、房型銷售比例等

---

## 👩‍💻 My Contributions 我的貢獻

- Developed backend APIs for hotel, room, order, and review modules  
  負責開發飯店、房型、訂單、評論等後端模組 API
- Designed MySQL database schema with JPA entity relationships  
  使用 JPA 設計資料表結構與關聯
- Built frontend dashboard UI with HTML, JS, Bootstrap  
  製作後台管理介面頁面（HTML, Bootstrap, JavaScript）
- Integrated frontend and backend via AJAX & JSON  
  前後端資料串接（AJAX 傳遞 JSON）
- Visualized data with Chart.js  
  利用 Chart.js 繪製折線圖與圓餅圖報表
- Collaborated on Postman / Swagger API testing  
  協助編寫與測試 API 文件（Postman, Swagger）

---

## 🚀 How to Run 執行方式

### Frontend 前端執行

```bash
# Clone the frontend repository
git clone https://github.com/Pei-ju/JAVA-Hotel.git
cd JAVA-Hotel

# Open home.html in browser (e.g., VS Code Live Server)
# 開啟 home.html，可使用 VS Code Live Server 瀏覽
```

### Backend 後端執行

```bash
# Clone backend repo
git clone https://github.com/Pei-ju/Staytion.git
cd Staytion

# Build and run Spring Boot
./mvnw spring-boot:run
```
