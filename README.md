# 🌤️ Weather App

Real‑time weather with animated conditions, a live clock, and a sleek, responsive UI.

## ✨ Highlights

- **📍 Location‑aware** weather that auto-detects your city
- **🌡️ Temperature** in Celsius (and Fahrenheit-ready)
- **🕐 Live clock** with current date
- **📅 Forecast summary** with key metrics
- **🎨 Animated UI** with modern gradients and motion
- **📱 Mobile‑first** responsive design

## 🚀 Quick Start

### Prerequisites

- Node.js 14+ and npm (or yarn)

### Setup

```bash
git clone <repository-url>
cd weatherApp-Reactjs-master
npm install
```

### Configure API Key

1. Create an account on [OpenWeatherMap](https://openweathermap.org/api)
2. Copy your API key
3. Update `src/apiKeys.js`:

```javascript
export default {
  key: "YOUR_API_KEY_HERE"
};
```

### Run Locally

```bash
npm start
```

App runs on `http://localhost:3000`

## 🧭 Usage

- The app loads your current location and shows live weather.
- Use the **search bar** to look up any city.
- Weather cards update with temperature, humidity, visibility, and wind.

## 🛠️ Tech Stack

- **React 16.13.1**
- **Axios** for HTTP requests
- **OpenWeatherMap API**
- **React Geolocated** for location access
- **React Live Clock**
- **React Animated Weather**

## 📁 Project Structure

```
weatherApp-Reactjs-master/
├── public/
│   └── index.html
├── src/
│   ├── App.js              # Root component
│   ├── currentLocation.js  # Main weather display
│   ├── forcast.js          # Search + forecast panel
│   ├── apiKeys.js          # API configuration
│   └── App.css             # Styling
└── README.md
```

## 🧪 Scripts

```bash
npm start    # development
npm build    # production build
npm test     # run tests
```

## 🌐 Browser Support

- Chrome, Firefox, Safari, Edge (latest)

## 🤝 Contributing

1. Fork the repo
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit your changes
4. Push and open a PR

## 📝 License

MIT License — see [LICENSE](LICENSE)

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/)
- [React Animated Weather](https://github.com/unicodeveloper/react-animated-weather)
- [React Geolocated](https://github.com/tim-soft/react-geolocated)

---

**Made with ❤️ using React**

**Developed by Pratiksha Hemant Samant**