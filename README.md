# **FSD_CT2**

👥 **Management Application**  
A full-stack MERN web application for managing student team members. Users can add, view, and manage member profiles including personal, academic, and professional details.

---

## 📌 Features

- Add new team members with:
  - Name, Role, Email, Registration Number, Degree Stream, Hobbies, Profile Image
- View all added members in a responsive grid layout
- View detailed profile for each member
- Persistent data storage using MongoDB Atlas
- Image upload functionality using Multer
- Clean and responsive UI with React & Tailwind CSS

---

## 🛠 Tech Stack

### **Frontend**
- React.js
- React Router DOM
- Axios

### **Backend**
- Node.js
- Express.js
- MongoDB Atlas
- Multer (for image uploads)

---

## 📂 Project Structure

```
root/
├── client/           # React frontend
│   ├── public/
│   ├── src/
│   │   ├── pages/    # AddMember, ViewMembers, MemberDetails
│   │   ├── App.js
│   │   └── index.js
├── server/           # Express backend
│   ├── models/
│   ├── routes/
│   ├── uploads/      # Stores uploaded images
│   ├── .env
│   └── server.js
```

---

## 🚀 Getting Started Locally

### 1. Setup backend

```bash
cd server
npm install
```

Create a `.env` file inside `server/` directory:

```
PORT=5000
MONGO_URI=<your-mongodb-connection-string>
```

Run backend:

```bash
npm start
```

---

### 2. Setup frontend

Open a new terminal:

```bash
cd client
npm install
```

Create a `.env` file inside `client/` directory:

```
REACT_APP_API_URL=http://localhost:5000/api
```

Run frontend:

```bash
npm start
```

---

## 🌐 Deployment

To deploy the application:

- Backend: Use [Render](https://render.com/)
- Frontend: Use [Vercel](https://vercel.com/) or [Netlify](https://netlify.com/)
- Update `.env` variables accordingly
- For image uploads in production, configure cloud storage (optional)

---



## 🙋‍♀️ Authors

- **Pragati**  
  RA2212704010041  
  CSE Core, SRMIST  
 

- **R. Thrisha**  
  RA2211056010166  
  CSE Core, SRMIST  
 

- **Jidnyesha**  
  RA2211056010167  
  CSE Core, SRMIST  
 

