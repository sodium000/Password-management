
## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

#Live Link : https://password-store-eosin.vercel.app/




# 🛠️ React + Express Full Stack Application

This is a **full stack web application** built with:

- 🧩 **Frontend:** React.js using [Vite](https://vitejs.dev/) for fast and modern development
- ⚙️ **Backend:** Node.js with [Express.js](https://expressjs.com/) for creating robust REST APIs

The project is structured with a clear separation between the frontend (`/client`) and backend (`/backend`) directories. It serves as a solid boilerplate or starter template for web applications where React handles the user interface and Express powers the server-side logic and API.

---

## 🧩 Project Structure

passwordManager/
├── passOp-mongo/ # React + Vite frontend and using backend + database 
└── passOp-localStroge/ # password save in local stroge 


---

## 🚀 Getting Started

### 📁 1. Clone the Repository

---

 # git clone https://github.com/sodium000/Password-management.git

⚙️ Backend Setup (Express.js)
📍 Navigate to backend folder

- cd backend

# 📦 Install Dependencies

- npm install

▶️ Run the Server

- npm run start

Or, if using nodemon for development:

- npx nodemon sever.js

# 📝 By default, the backend runs on: http://localhost:3000

🎨 Frontend Setup (React + Vite)
📍 Navigate to frontend folder


# 📦 Install Dependencies
 
- npm install

# ▶️ Run the Development Server

- npm run dev

📝 By default, Vite runs on: http://localhost:5173

🔄 API Connection
Make sure the frontend is configured to send requests to the correct backend URL (e.g., http://localhost:3000/api/...).
This is usually handled via an .env file or configuration variable.

# 📦 Build Frontend for Production


npm run build



# 📂 Example .env Files
# 🔧 For Backend (backend/.env)

PORT=3000
MONGO_URI=your_mongodb_connection_string

# 🎨 For Frontend (client/.env)

VITE_API_BASE_URL=http://localhost:3000


