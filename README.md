# Weather Forecast Web Page  

A simple **Weather Forecast Application** built using **HTML, CSS, and JavaScript**.  
It lets users select a **U.S. state** to view its **current weather conditions** and a **multi-day forecast**.  

---

##  Features  
✅ Dynamic dropdown with **U.S. states** (from Census API)  
✅ Live **weather + forecast** (from GoWeather API)  
✅ **Previous / Next** buttons for quick navigation  


## Technologies Used  
- **HTML5** – Page structure  
- **CSS3** – Styling and layout  
- **JavaScript (ES6)** – API requests, DOM updates, event handling  
- **[Census API](https://api.census.gov/)** – For U.S. states list  
- **[GoWeather API](https://goweather.xyz/)** – For weather forecast data

## How It Works  
1. On load, the app fetches U.S. states from the **Census API** and fills the dropdown.  
2. When a state is selected:  
   - Fetches weather data from **GoWeather API**.  
   - Displays **temperature, wind, description, and forecast**.  
3. Users can browse states using **Previous** / **Next** buttons. 
