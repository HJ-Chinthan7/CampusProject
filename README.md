# Campus Event Management System

##  Features
- **Admin Portal**: Create/manage events, attendance, reports
- **Student Portal**: Register events, view attendance, feedback
- **College-based isolation**
- **Full CRUD operations**
- **Responsive UI** (Tailwind + React 19)

##  Tech Stack
```
Frontend: React 19 + Vite + Tailwind CSS + React Router
Backend: Express.js + MongoDB + Mongoose
Auth: JWT + bcrypt
Deployment: Ready for Vercel/Netlify + Render/Railway
```

##  Quick Start

### Prerequisites
- Node.js 18+
- MongoDB (local or [MongoDB Atlas](https://mongodb.com/atlas))

### 1. Clone & Install
```bash
git clone <your-repo>
cd campus-event-management
npm run install-all
```

### 2. Environment
Copy `.env.example` to `.env`:
```
PORT=5000
JWT_SECRET=secretkey
```

### 3. Run
```bash
# Backend
npm run dev

# Frontend (new terminal)
cd client && npm run dev
```

Backend: `http://localhost:5000`
Frontend: `http://localhost:3000`

##  Demo Accounts
**Admin**: `admin@democollege1.edu` / `Admin1Pass!`

**Demo Colleges**: DemoCollege1-10

##  Live Demo
```
[Deployed Link - Update after deployment]
```

##  Project Structure
```
campus-event-management/
├── client/          # React 19 + Tailwind
├── server/          # Express + MongoDB
├── .env.example     # Environment vars
└── README.md
```

##  Scripts
```
npm run dev         # Start both (backend)
npm run server      # Backend only
cd client && npm run dev  # Frontend only
npm run migrate     # SQLite → MongoDB (if needed)
```

##  API Endpoints
```
POST /api/auth/admin-login
POST /api/auth/student-login
GET  /api/events (collegeId)
POST /api/registrations/:eventId/register
...
```

##  Deploy
**Frontend** (Vercel/Netlify): Static export
**Backend** (Render/Railway): Node + MongoDB add-on



---

