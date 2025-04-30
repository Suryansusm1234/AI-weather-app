# Weatherwise – AI Powered Weather App

**Weatherwise** is a sleek, modern weather application built with Next.js and React. It combines real-time weather data, a beautiful UI, and AI-powered outfit suggestions to help you plan your day smarter!

---

## 🌐 Live Demo

[Weatherwise Live App](#)

---

## ✨ Features

- **Real-time Weather:** Get instant weather updates for any city worldwide.
- **AI Outfit Suggestions:** Powered by Google Gemini, receive smart, context-aware clothing and accessory suggestions based on current weather.
- **Hourly Forecast:** See the next several hours at a glance with easy-to-read icons and precipitation chances.
- **Unit Toggle:** Switch between Celsius and Fahrenheit with a single click.
- **Modern, Responsive UI:** Built with Tailwind CSS and Lucide icons for a beautiful, accessible experience on any device.
- **Error Handling:** Friendly messages for loading, errors, and invalid searches.

---

## 🏗️ Tech Stack

- **Framework:** Next.js (React, App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Icons:** [Lucide React](https://lucide.dev/)
- **Weather Data:** [OpenWeatherMap API](https://openweathermap.org/api)
- **AI Suggestions:** [Google Gemini API](https://ai.google.dev/)
- **Fonts:** Geist Sans and Geist Mono (from Google Fonts)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/weatherwise.git
cd weatherwise
```


### 2. Install Dependencies

```bash
npm install
```


### 3. Set Up Environment Variables

Create a `.env.local` file in the root directory and add:

```env
NEXT_PUBLIC_OPENWEATHER_API_KEY=your_openweather_api_key
NEXT_PUBLIC_GEMINI_API_KEY=your_google_gemini_api_key
```

- Get your [OpenWeatherMap API key](https://home.openweathermap.org/api_keys)
- Get your [Google Gemini API key](https://ai.google.dev/)


### 4. Run the Development Server

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🖥️ Usage

- **Search for a City:** Enter a city name and press Enter or click the search icon.
- **View Weather:** Instantly see temperature, humidity, wind, rain, and a weather description.
- **Hourly Forecast:** Scroll horizontally to see the upcoming forecast.
- **Get AI Suggestions:** See fashion and accessory tips tailored to the weather, for both men and women.
- **Switch Units:** Click the °C/°F button in the header to toggle temperature units.

---

## 📸 Screenshots
**visit my [LinkedIn page](https://www.linkedin.com/in/suryansu-sanjeebani-mohanty)**

---

## 🗂️ Code Structure

```
/app
  ├── layout.tsx      # Root layout with fonts and metadata
  ├── globals.css     # Global Tailwind styles
  └── WeatherWise.tsx # Main weather app component (your provided code)
```


---

## ⚡️ How It Works

- **Weather Data:**
    - Fetches city coordinates using OpenWeatherMap’s Geocoding API.
    - Retrieves current weather and 7-hour forecast.
- **AI Suggestions:**
    - Sends weather details to Google Gemini (Generative AI) for clothing and accessory recommendations.
- **UI:**
    - Uses Lucide icons for weather visuals.
    - Responsive, accessible layout with Tailwind CSS.
- **State Management:**
    - React hooks (`useState`) for managing city, weather, forecast, AI suggestions, loading, and errors.

---

## 🛡️ License

MIT License. See [LICENSE](./LICENSE) for details.

---

## 🚧 Future Improvements

- **Weekly Forecast:** Add 7-day forecast with trends and charts.
- **Location Detection:** Auto-detect user’s current location for instant weather.
- **More Weather Details:** Add UV index, air quality, sunrise/sunset, etc.
- **Theme Support:** Dark/light mode and custom themes.
- **Offline Mode:** Cache recent searches and forecasts for offline viewing.
- **PWA Support:** Installable as a Progressive Web App.
- **Accessibility:** Further improve ARIA labels and keyboard navigation.
- **User Profiles:** Save favorite cities and personalized settings.
- **Push Notifications:** Severe weather alerts and daily summaries.
- **Multi-language Support:** Localize for global users.

---

## 🙏 Contributing

Contributions are welcome!
Open an issue or submit a pull request to help make Weatherwise even better.

---

## 📬 Contact

For feedback, support, or suggestions, open an issue or contact the maintainer.

---

Stay weather-wise, stay prepared!
**Weatherwise – AI Powered Weather App**

<div style="text-align: center">⁂</div>

[^2_1]: https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/48464239/4148ad72-cb7c-4f57-8934-5165983b8b79/paste.txt

