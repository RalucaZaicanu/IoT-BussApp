<<<<<<< HEAD
IoT_BusApp
==========

This is a **Node-RED** project that manages IoT-based bus tracking and monitoring. It integrates with Twilio and other APIs to provide real-time notifications and data visualization.  

## 🌟 Features  
- 📍 **Real-time GPS Tracking** – Monitors bus locations.  
- 📊 **Data Visualization** – Displays data on Node-RED dashboards.
- 🗺️ **Live Map** – Displays user locations, bus stations and bus locations.  
- 🔔 **Twilio Notifications** – Sends alerts via SMS when a bus reaches a stop.  
- ☁️ **Cloud Integration with Azure** – Syncs with cloud databases for storage, also has local storage.  

This project leverages Node-RED, a low-code, flow-based development tool, to process and visualize real-time bus data. Using APIs from tranzi.opendata, it retrieves live vehicle locations and integrates them with user location data. A pie chart on the Node-RED dashboard provides insights into the number of buses operating within a 2km radius from the user and other popular transit areas in Cluj-Napoca, highlighting real-time activity.

Additionally, the project features a live map that updates every minute, displaying buses, user location, and nearby bus stops. This visualization helps users track public transport more effectively. To enhance usability, bus timetables are incorporated, enabling SMS alerts via Twilio whenever a selected bus departs from the dispatcher.

All IoT data collected—such as bus locations, user coordinates, and notifications—is stored both locally and in Azure Blob Storage for backup and analysis. This combination of real-time tracking, interactive dashboards, and automated notifications ensures a seamless experience for users relying on public transportation in Cluj-Napoca.



=======
# Iot_BussApp
>>>>>>> b2c784fcec16f8860763fdf956af6bdc27dd9643
