# News Aggregator (MERN Stack)

## 📌 Overview
News Aggregator is a full-stack web application built using the **MERN stack (MongoDB, Express.js, React.js, and Node.js)**. It fetches the latest news from **NewsAPI** and displays it in an interactive UI. Users can browse news by categories, search for specific topics, and even save their favorite articles.

## 🚀 Features
- Fetch and display news articles from **NewsAPI**
- Category-based news filtering (e.g., Business, Technology, Sports, etc.)
- Search functionality to find specific news
<!-- - User authentication (Sign up/Login using JWT) -->
- Save favorite articles for later reading
- Responsive UI built with React and Tailwind CSS

## 🛠️ Tech Stack
### Frontend:
- React.js
- Redux (for state management)
- Axios (for API requests)
- Tailwind CSS (for styling)

### Backend:
- Node.js
- Express.js
<!-- - MongoDB with Mongoose (for database management)
- JWT (for authentication)
- bcrypt (for password hashing) -->

## 🔧 Installation and Setup

### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/your-username/news-aggregator.git
 cd news-aggregator
```

### 2️⃣ Backend Setup
```sh
 cd server
 npm install
```
#### Create a `.env` file inside `server` directory and add:
```
PORT=5000

API_KEY=your_newsapi_key
```

#### Start Backend Server
```sh
 nodemon server.js
```

### 3️⃣ Frontend Setup
```sh
 cd ../client
 npm install
```

#### Start React App
```sh
 npm run dev
```

## 📡 API Usage
To use **NewsAPI**, sign up at [NewsAPI.org](https://newsapi.org/) and get an API key. Then, update your `.env` file with `API_KEY`.

## 📷 Screenshots
(Add screenshots of your application here)

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or create a pull request.

## 📜 License
This project is licensed under the MIT License.

---

🚀 **Happy Coding!** 🎉

