# Staytion - Hotel Booking Management Dashboard

A full-featured hotel management system with frontend-backend separation. Developed as a team project, this system supports hotel and room management, booking orders, review moderation, and revenue analytics.  
Built with Java Spring Boot for backend APIs and HTML/CSS/JavaScript (Bootstrap) for frontend UI.

---

## Project Repositories

- Frontend Repo: [JAVA-Hotel](https://github.com/Pei-ju/JAVA-Hotel)  
  Java-based frontend with HTML, CSS, and Bootstrap. Admin dashboard with responsive UI and Chart.js visualizations.

- Backend Repo: [Staytion](https://github.com/Pei-ju/Staytion)  
  Java Spring Boot + MySQL backend. Provides RESTful APIs for hotel, room type, bookings, and reviews.

---

## Tech Stack

| Layer        | Technology                                  |
|--------------|----------------------------------------------|
| Frontend     | Java, HTML, CSS, Bootstrap                    |
| Backend      | Java, Spring Boot, Spring MVC, JPA           |
| Database     | MySQL                                        |
| Charts       | Chart.js                                     |
| Architecture | RESTful API, Frontend-Backend Separation     |
| Version Ctrl | GitHub, Git Branching                        |

---

## Key Features

- Hotel & Room Type Management  
  Add/edit/delete hotels and room types. Manage amenities and availability.

- Booking Order Management  
  View booking records, filter by date/status, export as Excel/PDF.

- Review Moderation  
  Review guest comments, reply to reviews, mark as responded, filter by rating.

- Dashboard Analytics  
  Revenue trends, room type distribution, monthly statistics with Chart.js.

- Responsive UI  
  Supports desktop and mobile views for admin.

---

## My Contributions

- Developed backend RESTful APIs using Spring Boot for hotel, room, order, and review modules.
- Designed database schema and implemented JPA entity relationships.
- Built frontend pages with Java, Bootstrap, and Chart.js.
- Integrated frontend and backend via AJAX and JSON.
- Visualized report data using Chart.js (line, pie charts).
- Assisted with API testing using Postman and Swagger.

---

## Screenshots

> Suggest adding a `screenshots/` folder with 3–5 demo images such as:
- Dashboard Overview
- Booking Orders Table
- Hotel/Room Management Page
- Review Moderation Interface
- Revenue Chart Visualization

---

## How to Run

### Frontend

```bash
# Clone frontend repo
git clone https://github.com/Pei-ju/JAVA-Hotel.git
cd JAVA-Hotel

# Open frontend (e.g., run in your Java environment or open index.html if applicable)
```
### Backend

```bash
# Clone backend repo
git clone https://github.com/Pei-ju/Staytion.git
cd Staytion

# Build and run Spring Boot
./mvnw spring-boot:run
```
