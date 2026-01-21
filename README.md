# Flightionary - Make It Happen ✈️

A modern flight booking and travel management web application that helps users discover destinations, book flights, and plan their perfect vacation.

## 📋 Overview

Flightionary is a comprehensive travel platform that combines flight booking with destination discovery. The application features a personality quiz to help users find their ideal travel destination, favorites management, ticket reservations, and a complete admin dashboard for managing flights, destinations, and users.

## ✨ Features

### For Users
- **Flight Search & Booking**: Browse and book flights to various destinations
- **Personality Quiz**: Answer questions to discover destinations that match your travel preferences
- **Destination Explorer**: View detailed information about tourist destinations with different categories (beach, cultural, religious, gastronomic, adventure, rural)
- **Favorites**: Save your favorite destinations for easy access
- **Profile Management**: Manage your personal information and profile picture
- **Reservation History**: View and manage all your flight tickets and bookings
- **User Authentication**: Secure login and registration system

### For Administrators
- **Flight Management**: Add, edit, and remove flights
- **Destination Management**: Manage tourism destinations and categories
- **User Monitoring**: View user search history and activity logs
- **Admin Dashboard**: Centralized control panel for all administrative tasks

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript (ES6+)**: Application logic and interactivity
- **Bootstrap 5.3.3**: UI components and responsive grid system
- **Font Awesome 6.4.0**: Icons and visual elements

### Architecture
- **MVC Pattern**: Model-View separation for organized code structure
  - **Models**: `users.js`, `flights.js`, `destinations.js`, `quiz.js`, `type.js`, `logs.js`
  - **Views**: Separate view files for each page component
- **LocalStorage**: Client-side data persistence
- **JSON**: Data storage format for flights, destinations, quiz questions, and tourism types

### Key Libraries
- Bootstrap CSS & JavaScript
- Font Awesome Icons
- Native JavaScript (no additional frameworks)

## 📁 Project Structure

```
├── index.html                  # Main landing page
├── css/                        # Stylesheets
│   ├── navbar.css
│   ├── main.css
│   ├── footer.css
│   ├── login.css
│   ├── quiz.css
│   └── ...
├── html/                       # Application pages
│   ├── login.html
│   ├── register.html
│   ├── flight.html
│   ├── quiz.html
│   ├── profile.html
│   ├── reservations.html
│   ├── favourites.html
│   ├── admin.html
│   └── ...
├── js/
│   ├── models/                 # Data models
│   │   ├── users.js
│   │   ├── flights.js
│   │   ├── destinations.js
│   │   ├── quiz.js
│   │   ├── type.js
│   │   └── logs.js
│   ├── views/                  # View controllers
│   │   ├── LoginView.js
│   │   ├── MainPageView.js
│   │   ├── FlightsView.js
│   │   ├── QuizView.js
│   │   └── ...
│   └── data/                   # JSON data files
│       ├── flight.json
│       ├── destinations.json
│       ├── quiz.json
│       └── type.json
├── img/                        # Images and assets
└── fonts/                      # Custom fonts
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Installation

1. Clone or download the repository:
```bash
git clone <repository-url>
cd Projeto-POO
```

2. Open the project in a web browser:
   - Option 1: Open `index.html` directly in your browser
   - Option 2: Use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

3. Navigate to `http://localhost:8000` (if using a local server)

### Default Admin Credentials
```
Email: admin@admin.com
Password: admin123
```

## 💡 How to Use

### For Regular Users
1. **Register** a new account or **Login** with existing credentials
2. Browse available **flights** and destinations
3. Take the **personality quiz** to find destinations that match your preferences
4. **Book flights** to your chosen destinations
5. Save destinations to your **favorites**
6. View your **reservations** and manage your **profile**

### For Administrators
1. Login with admin credentials
2. Access the admin dashboard
3. Manage flights (add/edit/delete)
4. Manage destinations and tourism types
5. Monitor user activity and search logs

## 📦 Data Storage

The application uses **LocalStorage** to persist data:
- User accounts and authentication
- Flight information
- Destinations and tourism types
- User favorites and reservations
- Activity logs

Data is automatically synchronized between sessions.

## 🎨 Design Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and intuitive user interface
- **Brand Colors**: Custom color scheme with primary accent color (#D90429)
- **Interactive Elements**: Smooth transitions and hover effects
- **User-Friendly**: Easy navigation with dropdown menus and clear call-to-actions

## 🔒 Security Note

This is an educational project. For production use, consider implementing:
- Server-side authentication
- Password encryption
- HTTPS protocol
- Input validation and sanitization
- Database instead of LocalStorage

## 👥 Contributors

This project was developed by:

### Development Team

- **José Guedes** - Full-Stack Developer [40230110@esmad.ipp.pt]
- **Mário Dias** - Full-Stack Developer [40230356@esmad.ipp.pt]


## 📝 License

This is an academic project developed for POO (Object-Oriented Programming) course at Instituto Politécnico do Porto.

## 👥 Contributing

This is a student project. For questions or suggestions, please contact the development team.

---

**Flightionary** - Your journey starts here! 🌍✨
