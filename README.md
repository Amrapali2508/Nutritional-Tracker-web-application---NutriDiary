# NutriDiary

NutriDiary is a comprehensive nutrition tracking application designed to help users monitor their dietary habits, set nutritional goals, and maintain a healthy lifestyle. This project consists of a **Node.js backend**, a **React.js frontend**, and a **PostgreSQL database**.

## Features
- User authentication and profile management.
- Track daily calorie intake and nutritional values.
- Search and log meals from a food database.
- See data wise intake of food
- Set personalized dietary goals.


---

## Tech Stack

### Backend
- **Node.js** with Express.js
- mongoDB  for database management
- Sequelize ORM for database operations

### Frontend
- **React.js** with functional components
- State management using Context API
- Axios for API communication

---

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or later)
- npm (comes with Node.js) or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd NutriDiary
   ```

2. **Set up the Backend**
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file using the provided `.env.example`.
   - Run database migrations and seed data:
     ```bash
     npx sequelize-cli db:migrate
     npx sequelize-cli db:seed:all
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Set up the Frontend**
   - Navigate to the frontend directory:
     ```bash
     cd ../frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

4. **Access the application**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend: [http://localhost:8080](http://localhost:8080)

---

## Usage

1. **User Registration and Login**
   - Create an account or log in with existing credentials.
   
2. **Log Meals**
   - Use the search feature to find food items and log them to your daily intake.

3. **Set Goals**
   - Customize daily calorie and macronutrient targets.

4. **Monitor Progress**
   - View charts and analytics to track dietary trends.

---

## Project Structure

### Backend
```
backend/
|-- app.js
|-- config/
|-- controllers/
|-- middleware/
|-- models/
|-- routes/
|-- .env.example
```

### Frontend
```
frontend/
|-- src/
    |-- components/
    |-- pages/
    |-- utils/
|-- public/
|-- package.json
```

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contributions
Contributions are welcome! Feel free to submit a pull request or open an issue.

---



