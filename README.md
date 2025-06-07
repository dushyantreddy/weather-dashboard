
# Weather Dashboard

A responsive React web app that lets users search for any city’s current weather and 5-day forecast using the OpenWeatherMap API.

---

## Tech Stack

- **Framework:** React (Create React App)  
- **Data Fetching:** JavaScript Fetch API  
- **Styling:** CSS Flexbox & Grid, Media Queries  
- **Version Control:** Git & GitHub  
- **Deployment:** GitHub Pages (via gh-pages)

---

## Features & Functionality

1. **City Search**  
   - Enter any city name to view its weather.  
2. **Current Weather Display**  
   - Shows temperature (°C), humidity, wind speed, and description.  
3. **5-Day Forecast**  
   - Displays midday forecast for the next 5 days in a responsive grid.  
4. **Search History**  
   - Saves your last five searches in localStorage for quick recall.  
5. **Mobile-First Responsive Design**  
   - Layout adapts from single-column (mobile) to multi-column (desktop).

---

## Setup & Run Locally

1. **Clone the repo**  
   ```bash
   git clone https://github.com/dushyantreddy/weather-dashboard.git
   cd weather-dashboard


2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Add your OpenWeatherMap API key**

   * Create a file named `.env` in the project root.
   * Add the following line (replace with your own key):

     ```
     REACT_APP_OPENWEATHER_KEY=YOUR_API_KEY_HERE
     ```

4. **Start the development server**

   ```bash
   npm start
   ```

   Opens at `http://localhost:3000`.

5. **Build for production**

   ```bash
   npm run build
   ```

   Static files go into the `build/` folder.

---

## Deployment to GitHub Pages

1. **Install gh-pages** (if you haven’t already):

   ```bash
   npm install --save-dev gh-pages
   ```

2. **Configure** your `package.json`:

   ```jsonc
   {
     "homepage": "https://dushyantreddy.github.io/weather-dashboard",
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
     }
   }
   ```

3. **Deploy**:

   ```bash
   npm run deploy
   ```

   Your live site will be available at:
   `https://dushyantreddy.github.io/weather-dashboard/`

---

## References

* **React Docs:** [https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)
* **OpenWeatherMap API:** [https://openweathermap.org/api](https://openweathermap.org/api)
* **gh-pages npm:** [https://www.npmjs.com/package/gh-pages](https://www.npmjs.com/package/gh-pages)
* **MDN (Flexbox & Grid):** [https://developer.mozilla.org/](https://developer.mozilla.org/)

```
```
