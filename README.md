# Milan Food Donation Platform – Backend

This is the backend for the Milan Food Donation Platform, built with Node.js, Express, and MongoDB. It provides RESTful API endpoints for managing food donations and contact messages.

## 🌐 Live API

[https://milan-backend.onrender.com](https://milan-backend.onrender.com)

## 🛠️ Tech Stack

- Node.js
- Express
- MongoDB Atlas
- Mongoose
- CORS

## 🚀 Features

- Add and retrieve food donations
- Add and retrieve contact messages
- Input validation and error handling

## ⚙️ Environment Variables

Create a `.env` file in the project root:


## 🧑‍💻 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com/Abhinav9826/milan-backend.git
   cd milan-backend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up your `.env` file** (see above).

4. **Start the server:**
   ```bash
   npm start
   ```

   The server will run on `http://localhost:5000` by default.

## 📦 Deployment

Deployed on [Render](https://render.com/).

## 📄 API Endpoints

| Method | Endpoint         | Description                |
|--------|------------------|----------------------------|
| GET    | `/donations`     | Get all donations          |
| POST   | `/donations`     | Add a new donation         |
| GET    | `/contact`       | Get all contact messages   |
| POST   | `/contact`       | Add a new contact message  |

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

## 📄 License

[MIT](LICENSE)
