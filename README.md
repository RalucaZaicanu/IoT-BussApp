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
Flows:
![image](https://github.com/user-attachments/assets/13f93d61-5a27-48d8-b5f0-9a5fe4024524)

Live Map: 
![image](https://github.com/user-attachments/assets/2ba37cfc-ed26-4fee-bfa4-b594682e5501)
![image](https://github.com/user-attachments/assets/13041c0d-31c3-4941-9f74-125183c8bcae)

PieChart: 
![image](https://github.com/user-attachments/assets/42688214-1555-4baf-a99b-b0252bfd572a)


Messages: 

![Imagine WhatsApp 2025-02-04 la 23 50 28_762a3a65](https://github.com/user-attachments/assets/c08f6448-5456-4fc0-b030-7cd8f331b5a4)





=======
# Iot_BussApp
>>>>>>> b2c784fcec16f8860763fdf956af6bdc27dd9643
