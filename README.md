# Invoice Billing App 🧾

A full-stack web application that helps freelancers and small businesses manage clients and generate invoices with ease. Built with React, Node.js, and MySQL, this app includes client management, invoice tracking, PDF generation, and secure authentication.

## 🚀 Features

- 🔐 User authentication using JWT stored in localstorage
- 👥 Client management with full CRUD operations
- 🧾 Invoice creation and tracking with status updates (Paid/Pending)
- 📄 PDF generation of invoices for download or print
- 📊 Dashboard with real-time insights on total revenue, clients, and pending payments
- 💾 Data persistence using MySQL and Sequelize ORM
- 🎨 Clean, responsive UI using custom CSS (no frameworks)

## 🛠️ Tech Stack

**Frontend**
- ReactJS
- React Router
- Context API
- CSS

**Backend**
- Node.js
- Express.js
- MySQL
- Sequelize ORM
- JWT for authentication

## 📂 Folder Structure

```
invoice-billing-app/
├── frontend/     # ReactJS app for UI
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
├── backend/      # Node.js + Express backend
│   |---config  
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── package.json
└── README.md
```

## 🎯 Altogether

The Invoice Billing App brings together frontend and backend technologies to deliver a robust solution for managing client records and financial documents. Users can log in, manage clients, create invoices, generate professional PDFs, and track overall revenue — all from one intuitive dashboard.

## ⚙️ Installation

1. **Clone the repository**

```
git clone https://github.com/your-username/invoice-billing-app.git
cd invoice-billing-app
```

2. **Install frontend dependencies**

```
cd frontend
npm install
```

3. **Install backend dependencies**

```
cd ../backend
npm install
```

4. **Set up environment variables**

Create a `.env` file inside the `backend/` folder and configure:

```
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=invoiceapp
JWT_SECRET=your_jwt_secret
```

5. **Run the backend server**

```
node server.js
```

6. **Run the frontend**

```
cd ../frontend
npm start
```

## 📄 .gitignore Suggestions

```
node_modules/
.env
build/
dist/
.DS_Store
```
