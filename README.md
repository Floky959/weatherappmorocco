# 🌤️ Weather App Morocco

A modern, responsive weather application built with React.js that provides real-time weather information for Moroccan cities with a beautiful glassmorphism UI design.

## 🚀 Live Demo

🔗 **[View Live Demo](https://ayoubmoufak.dev/weatherappmorocco/)**

## ✨ Features

### 🎨 **Modern UI/UX**
- **Glassmorphism design** with backdrop blur effects
- **Dynamic gradients** that change based on weather conditions
- **Responsive design** for all device sizes
- **Smooth transitions** and hover effects

### 🌍 **Weather Information**
- **Current weather** with real-time updates
- **5-day forecast** with daily predictions
- **Hourly forecast** for the next 8 hours
- **Detailed metrics**: humidity, wind speed, visibility, pressure
- **Sunrise/sunset times**
- **Temperature min/max** for today
- **Precipitation probability**

### 🔍 **Smart Search**
- **Autocomplete search** for Moroccan cities
- **Real-time filtering** with dropdown suggestions
- **Instant city selection**

### ⏰ **Real-time Elements**
- **Live clock** showing current time
- **Current date display** with auto-updates
- **Dynamic weather icons** based on conditions

## 🛠️ Technologies Used

- **React.js** - Frontend framework
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Modern icon library
- **OpenWeatherMap API** - Weather data source
- **GitHub Pages** - Deployment platform

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### 1. Clone the repository
```bash
git clone https://github.com/Floky959/weatherappmorocco.git
cd weatherappmorocco
```

### 2. Install dependencies
```bash
npm install
```

### 3. Get your API key
1. Visit [TMDB]((https://www.themoviedb.org/))
2. Sign up for a free account
3. Get your API key

### 4. Configure API key
Replace the API key in `src/componants/api.js`:
```javascript
const apiKey = 'YOUR_TMDB_API_KEY_HERE';
```

### 5. Start the development server
```bash
npm start
```

The app will open at `http://localhost:3000`

## 🚀 Deployment

### Deploy to GitHub Pages
```bash
# Install gh-pages
npm install --save-dev gh-pages

# Add to package.json
"homepage": "https://yourusername.github.io/moviesscope",

# Deploy
npm run deploy
```

⭐ **Star this repository if you found it helpful!**
