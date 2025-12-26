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
1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Get your API key

### 4. Configure API key
Replace the API key in `src/componants/Weater.jsx`:
```javascript
const apiKey = 'YOUR_OPENWEATHERMAP_API_KEY_HERE';
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
"homepage": "https://yourusername.github.io/weatherappmorocco",

# Deploy
npm run deploy
```


### Comprehensive Weather Data
- Current temperature with "feels like"
- Humidity and wind speed
- Atmospheric pressure
- Visibility distance
- UV index and weather descriptions

### Smart City Search
- Search through 100+ Moroccan cities
- Real-time autocomplete suggestions
- Instant weather updates on city selection

## 🔄 API Integration

The app integrates with:
- **OpenWeatherMap Current Weather API** - Real-time weather data
- **OpenWeatherMap 5-Day Forecast API** - Extended forecasts
- **Morocco Cities API** - Comprehensive list of Moroccan cities

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for weather data API
- [Tailwind CSS](https://tailwindcss.com/) for styling framework
- [Lucide React](https://lucide.dev/) for beautiful icons
- [Morocco Cities API](https://github.com/mboussaid/Maroc_Regions_Villes_API) for city data

⭐ **Star this repository if you found it helpful!**
