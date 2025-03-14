# Node-api
This is a Node.js API project using MongoDB

ReadMe
## 📌 Project Name  
**Javlonbek Node API**  

### 📖 Description  
This project is a Node.js-based API using MongoDB as a database. It supports CRUD operations and is designed for scalability.  

### 🚀 Features  
✅ User authentication (JWT)  
✅ MongoDB database integration  
✅ RESTful API structure  
✅ Error handling and validation  
✅ Deployment-ready  

### 🛠️ Technologies  
- **Node.js**  
- **Express.js**  
- **MongoDB & Mongoose**  
- **JWT for authentication**  

### 📦 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/JavlonbekGoziev/node-api.git
   cd node-api
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Configure `.env` file:  
   ```
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/javlonbek_api
   JWT_SECRET=super-strong-secret-key-123

   ```  
4. Run the server:  
   ```bash
   npm start
   ```  

### 🔗 API Endpoints  
| Method | Endpoint         | Description            |
|--------|-----------------|------------------------|
| POST   | `/users`    | Create a new user      |
| GET    | `/users`    | Get all users         |
| GET    | `/users/:id` | Get a user by ID      |
| PUT    | `/users/:id` | Update a user        |
| DELETE | `/users/:id` | Delete a user        |

### 📤 Deployment  
You can deploy this project on **Heroku, Vercel, or any cloud provider**.  

### 👨‍💻 Author  
- **Javlonbek Goziev**  
- [GitHub](https://github.com/JavlonbekGoziev)  
- [LinkedIn](https://www.linkedin.com/in/javlonbek-goziev-0049aa2ab)  

