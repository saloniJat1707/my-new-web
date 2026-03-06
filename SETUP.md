# 🚀 Quick Setup Guide

## Step 1: Install Backend Dependencies

```bash
cd backend
npm install
```

## Step 2: Start MongoDB

### Option A: Local MongoDB
Make sure MongoDB is running on your system:
```bash
mongod
```

### Option B: MongoDB Atlas (Cloud)
1. Create account at https://www.mongodb.com/cloud/atlas
2. Create a cluster
3. Get connection string
4. Update MONGODB_URI in backend/.env

## Step 3: Start Backend Server

```bash
cd backend
npm start
```

Backend will run on: http://localhost:5000

## Step 4: Open Frontend

### Option A: Direct File
Simply open `frontend/index.html` in your browser

### Option B: Local Server (Recommended)
```bash
cd frontend
python -m http.server 8000
```
Or
```bash
npx http-server frontend -p 8000
```

Frontend will run on: http://localhost:8000

## 🎉 Done!

Your portfolio is now running!
- Frontend: http://localhost:8000
- Backend API: http://localhost:5000

## 📝 Test Contact Form

1. Go to Contact section
2. Fill the form
3. Submit
4. Check MongoDB for saved message

## 🔍 View Saved Messages

Visit: http://localhost:5000/api/contacts

## ⚠️ Troubleshooting

### MongoDB Connection Error
- Make sure MongoDB is running
- Check MONGODB_URI in .env file

### CORS Error
- Make sure backend is running on port 5000
- Check frontend is making requests to correct URL

### Form Not Submitting
- Open browser console (F12)
- Check for error messages
- Verify backend is running

## 📱 Mobile Testing

Open on your phone:
- Find your computer's IP address
- Access: http://YOUR_IP:8000

---

Need help? Check README.md for detailed documentation!
