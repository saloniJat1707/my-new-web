# 🌟 Professional Portfolio - Saloni Jat

A modern, responsive portfolio website with full-stack implementation featuring smooth animations, contact form with backend API, and MongoDB database integration.

## ✨ Features

### Frontend
- 🎨 Modern, responsive design with smooth animations
- 🌈 Gradient effects and hover animations
- 📱 Mobile-friendly with hamburger menu
- ⚡ Smooth scrolling and section transitions
- 🎯 Interactive skill progress bars
- 💼 Project showcase cards
- 📧 Contact form with real-time validation

### Backend
- 🚀 RESTful API built with Express.js
- 🗄️ MongoDB database integration
- ✅ Form validation and error handling
- 🔒 CORS enabled for security
- 📊 Contact message storage and retrieval

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3 (Custom animations & gradients)
- Vanilla JavaScript
- Font Awesome Icons

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- dotenv

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### Backend Setup

1. Navigate to backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables:
- Edit `.env` file
- Update `MONGODB_URI` with your MongoDB connection string

4. Start the server:
```bash
npm start
```

For development with auto-reload:
```bash
npm run dev
```

Server will run on `http://localhost:5000`

### Frontend Setup

1. Navigate to frontend directory:
```bash
cd frontend
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server -p 8000
```

3. Access the portfolio at `http://localhost:8000`

## 🗄️ Database Schema

### Contact Model
```javascript
{
  name: String (required),
  email: String (required),
  subject: String (required),
  message: String (required),
  createdAt: Date (default: now)
}
```

## 🔌 API Endpoints

### POST /api/contact
Submit a contact form message
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "subject": "Project Inquiry",
  "message": "Hello, I'd like to discuss..."
}
```

### GET /api/contacts
Retrieve all contact messages (Admin)

### DELETE /api/contact/:id
Delete a specific contact message

## 🎨 Customization

### Colors
Edit CSS variables in `frontend/css/style.css`:
```css
:root {
    --primary-color: #00d4ff;
    --secondary-color: #0099ff;
    --dark-bg: #0a0e27;
    --light-bg: #1a1e3e;
}
```

### Content
- Update personal information in `frontend/index.html`
- Modify skills, projects, and contact details
- Add your own project cards

### Backend
- Extend API endpoints in `backend/server.js`
- Add new models for blog posts, testimonials, etc.

## 📱 Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## 🚀 Deployment

### Frontend
Deploy to:
- Netlify
- Vercel
- GitHub Pages
- AWS S3 + CloudFront

### Backend
Deploy to:
- Heroku
- Railway
- Render
- AWS EC2/Elastic Beanstalk

### Database
- MongoDB Atlas (recommended for production)
- Self-hosted MongoDB

## 📝 Environment Variables

Create `.env` file in backend directory:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

## 🔒 Security Notes

- Never commit `.env` file
- Use environment variables for sensitive data
- Enable CORS only for trusted domains in production
- Implement rate limiting for API endpoints
- Add authentication for admin routes

## 📄 License

MIT License - Feel free to use this portfolio template for your own projects!

## 👤 Author

**Saloni Jat**
- Email: salonijat1707@gmail.com
- LinkedIn: linkedin.com/in/saloni-jat

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## ⭐ Show your support

Give a ⭐️ if you like this project!

---

Made with ❤️ by Saloni Jat
