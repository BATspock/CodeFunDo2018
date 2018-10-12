# CodeFunDo++ 2018 - Team *Paranormal Penguins*

## 'Floodlights' - Minimizing the impact of floods

### Introduction
Floods are among the most common (and most devastating) of natural disasters. In fact, [this report](https://reliefweb.int/sites/reliefweb.int/files/resources/COP21_WeatherDisastersReport_2015_FINAL.pdf) presented by the Centre for Research on the Epidemiology of Disasters concluded that between 1995 and 2015, floods accounted for nearly 43% of all natural disasters.

With global warming on the rise, floods are posing enormous threats to life and property, and low-lying areas are consistently at risk of being inundated. An obvious yet effective mechanism to combat, and perhaps mitigate the effects of these floods would be to constantly monitor regional weather patterns, in an attempt to _predict_ the likelihood of a flood. Doing this would enable local authorities, response teams, and disaster management centres to take the right course of action at the right time, with minimum delay. But predicting a flood will not prevent it. Millions of people will be at risk, and taking timely action could go a long way in minimizing damage.

### Our Solution
**FLOODLIGHTS** is our effort to bring out what we think could be a small step towards "managing" floods. 
A **web-based application**, it is meant to be used by local authorities or response teams to 
- Monitor weather data to look out for possible flooding, and 
- Manage and co-ordinate rescue efforts in the event of a flood.

### Features
1. **Prediction** Perhaps the most important feature of all, it will emphasise on analysing weather patterns to decide if there is a risk of flooding (in the region of use) in the near future. Implementing this (in the form of a deep learning / image processing model) will require access to 
   - publicly available datasets containing historical data - i.e. records of previous floods and their preceding weather conditions
   - live weather information
   > [This research publication](https://www.sciencedirect.com/science/article/pii/0309170888900437) details a mathematical modeling system for predicting floods in India and Bangladesh
   > [This research publication](https://www.researchgate.net/publication/292980782_Flood_Disaster_in_India_An_Analysis_of_trend_and_Preparedness) analyses floods in India.
   > Datasets that we found [here](https://catalog.data.gov/dataset/ncdc-storm-events-database), [here](https://old.datahub.io/dataset/india-weather-data), [here (from the recent floods in Kerala)](https://www.kaggle.com/biphili/india-s-rainfall-kerala-flood) and [here](https://www.kaggle.com/rajanand/rainfall-in-india) could provide us with a starting point.
   > [THIS](https://www.rmsi.com/products/india-floodrisk/) product is also a helpful tool.
   
2. **SMS Alerts** to residents of potentially vulnerable areas, informing them about the possibility of a flood, and **also detailing safe zones, or high-lying areas* that could provide shelter.**
   - Basic analysis of altitudes / elevations from any map would suffice here.
   
3. **Enabling donations towards relief funds**, i.e. providing ONE link that people around the world could access to contribute towards helping victims.
   - This could be accomplished by using a payment gateway.
   
4. **An _emergency_ feature** that allows those in need of urgent attention to send out a request for a pickup/evacuation. 
   - This will require the affected person to send an SMS to a fixed number, providing their details. Some form of analysis must be done to verify the authenticity of such requests and also to prioritise between multiple requests.
   
5. **Enabling easy and cost-effective rescue operations** is highly necessary. Every helicopter-mission costs **crores** of rupees and time and money are both of the essence during floods. 
   - We plan to build a **thermal-imaging based system that can be mounted on small drones.** These drones would then scout the affected locations and pinpoint locations of humans. Rescue efforts can then be initiated depending on accessibility of victims, urgency, and density of affected people. 


6. **Discussion forums / Broadcasts and Announcements** to facilitiate easier communication with the general public and also to provide a common medium for rescuers, victims, or families of victims to seek help or reach out to others. 


These are the 6 main features that **Floodlights** will provide, which could, if used effectively, mitigate the impact of floods. 
