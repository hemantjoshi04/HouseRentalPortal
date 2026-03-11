# House Rental Portal

🏠 **A simplified, fully functional house rental platform for demonstration purposes**

Built with Spring Boot (backend) and React (frontend), this demo version showcases the core functionality of a house rental portal without the complexity of authentication and authorization.

## ✨ Demo Features

- **View Properties**: Browse available rental properties with details
- **Add Properties**: Simple form to add new rental properties  
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Updates**: Properties are immediately visible after adding
- **Sample Data**: Pre-loaded with sample properties for demonstration

## 🛠️ Tech Stack

### Backend
- **Spring Boot 3.2.0** - Main framework
- **Spring Data JPA** - Database operations
- **Maven** - Build tool

### Frontend
- **React 18** - UI framework
- **React Router** - Routing
- **Axios** - HTTP client

## 🚀 Quick Start (No Database Setup Required!)

### Prerequisites
- **Java 17+** (JDK)
- **Node.js 16+** 
- **Maven** (usually comes with Java)

### 📜 Step 1: Start the Backend
```bash
cd backend
./mvnw spring-boot:run
```
*On Windows, use: `mvnw.cmd spring-boot:run`*

✅ **Backend will start on:** `http://localhost:8081`  

### 🎨 Step 2: Start the Frontend
```bash
cd frontend
npm install
npm start
```

✅ **Frontend will start on:** `http://localhost:3000`  
✅ **Application is ready to use!**

### 🎆 That's It!
Open your browser to `http://localhost:3000` and start exploring the house rental portal!

---

## 📱 What You Can Do

1. **View Properties** - See pre-loaded sample properties on the homepage
2. **Add New Property** - Click "Add Property" to create a new rental listing
3. **Responsive Design** - Try it on mobile and desktop
4. **Real-time Updates** - Added properties appear immediately

---

## 📊 API Endpoints (Demo)

### Properties
- `GET /api/properties` - Get all properties
- `POST /api/properties/demo` - Add new property (simplified)
- `GET /api/properties/{id}` - Get property by ID

### H2 Database Console (Optional)
- `GET /h2-console` - Access in-memory database console
- **JDBC URL:** `jdbc:h2:mem:testdb`
- **User:** `sa`
- **Password:** *(leave empty)*

---

## ✨ Demo Features Implemented

✅ **Property Listing** - View all available properties  
✅ **Add Properties** - Simple form to add new rentals  
✅ **Responsive Design** - Works on all devices  
✅ **Sample Data** - Pre-loaded with demo properties  
✅ **Real-time Updates** - Instant property visibility  
✅ **H2 Database** - No setup required  
✅ **Material-UI** - Modern, clean interface  
✅ **CORS Enabled** - Frontend-backend communication  

---

## 📝 Notes for Teacher/Evaluator

- **Sample Data Included** - Properties are pre-loaded on startup
- **Full Stack Working** - Both REST API and React frontend functional
- **Easy to Run** - Just two commands to start everything

---

## 🔧 Troubleshooting

**Backend won't start?**
- Ensure Java 17+ is installed
- Check if port 8081 is free
- Try: `mvnw clean spring-boot:run`

**Frontend won't start?**
- Ensure Node.js 16+ is installed
- Check if port 3000 is free
- Try: `npm install --force`

**Properties not loading?**
- Ensure backend is running on port 8081
- Check browser console for errors
- Verify CORS is working

---

## 📚 Author

**Two Prominent Contributors:**
1) Parvesh Mehla
2) Sahil Sethi

House Rental Portal 


