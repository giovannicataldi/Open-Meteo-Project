# Open-Meteo-Project
Welcome to my project!
Here, I explored the best times/seasons to travel for 5 different U.S. cities: Los Angeles, New York, Chicago, Miami, and Seattle.

This project analyzes **5 years of historical weather data** (2020-2025) to determine:  
- **Best months/seasons** to visit each city  
- **Weather risks** (heatwaves, heavy rain) to avoid  
- **Comfort scores** (0-100) combining temperature, precipitation, and wind

---

### Data Sources  
- **Open-Meteo API**: Hourly weather data (temperature, precipitation amounts, wind speeds, etc.)  
- **Timeframe**: 2019-2024  

---

### Methodology  
1. **Travel Score** (0-100): a mix of scores from a temperature score, a precipiation score, and a wind score, along with respective weights of 50%, 30%, and 20% for each.
This travel score indicates how desirable it would be to travel to said destination. On a scale from 0-100, the higher the score, the more desirable it is to travel there.
