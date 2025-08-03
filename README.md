# 💸 Smart Budget Analyzer

A Spring Boot-based backend project to help users track, analyze, and improve their monthly spending behavior. 

---

## 🚀 Features
- Record spending transactions
- Analyze spending habits
- Suggest personalized monthly budgets
- Notify users when spending exceeds limits
- Redis caching for performance boost

---

## 🏗️ Tech Stack

| Purpose        | Tech                      |
|----------------|---------------------------|
| Backend        | Spring Boot, Spring Data JPA |
| Database       | PostgreSQL                 |
| Caching        | Redis                      |
| Scheduling     | Spring Scheduler           |
| Auth           | JWT                        |
| Container      | Docker, Docker Compose     |

---

## 📚 API Endpoints

| Method | Endpoint                   | Description                    |
|--------|----------------------------|--------------------------------|
| POST   | `/api/transactions`        | Add new transaction            |
| GET    | `/api/transactions`        | Get transactions by month      |
| GET    | `/api/budget/summary`      | Budget summary by category     |
| POST   | `/api/budget/suggestion`   | Suggest budget for next month  |
| GET    | `/api/analysis`            | Spending behavior insights     |

---

## 📦 Project Structure (N-Layers)
```
src/
├── controller/
├── service/
├── repository/
├── model/
├── dto/
└── config/
```
---

## 🧪 How to Run (with Docker)
```bash
git clone https://github.com/yourname/smart-budget-analyzer
cd smart-budget-analyzer

# Build & Run
docker-compose up --build
```
> Redis will be available at localhost:6379, PostgreSQL at localhost:5432

---

🔮 Future Improvements
- Machine Learning for behavior prediction

- Notification via Firebase

- React Frontend Dashboard

---

👨‍💻 Author
- SageDev
