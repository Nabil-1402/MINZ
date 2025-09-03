# London Pollution Visualiser

A Java-based desktop application developed as a group project to visualise and analyse air pollution data across London. This tool provides an interactive map and data views to explore levels of various pollutants from 2018 to 2023.

## Features

### 1. Welcome Screen
The application starts with a welcoming interface that guides users to the main functionalities. By clicking the buttons in the middle of the window it explains what each application in the programme does.
![Welcome Screen](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.39.33.png?raw=true) 


### 2. Main Navigation
From the welcome window, users can seamlessly navigate to the three core parts of the application:
- **Map Visualiser**: View pollution data on an interactive map.
- **Pollution Statistics**: Analyse trends and get aggregated data.
- **Grid Data Viewer**: Query specific coordinates for precise pollution levels.

![Main Navigation](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.46.20.png?raw=true)


### 3. Interactive Map Visualiser
The core feature of our application allows for dynamic exploration of pollution data.

- **Select a Pollutant**: Choose from NO₂, PM10, or PM2.5 via a drop-down menu.
![Pollutant Dropdown](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.46.47.png?raw=true)

- **Select a Year**: Choose a year from 2018 to 2023 to view historical data.
![Year Dropdown](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.46.54.png?raw=true)

- **Visualise on Map**: Once a pollutant and year are selected, the map updates to display colour-coded pollution levels across London.
![Map Visualisation](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.47.16.png?raw=true)

- **Click for Details**: Click on any data point on the map to see the exact pollution level for that location. As seen at the top of the image above.

- **Filter By Pollution Level**: by chosing from the filter drop down menu you can filter which level of pollution is shown on the map
![Filter Drop Down](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.47.27.png?raw=true)
![Filtered Map View](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.47.38.png?raw=true)



### 4. Pollution Statistics
This section provides analytical tools to understand the data better. Users can select a year and pollutant to view:
- Average Pollution
- Highest Pollution
- Pollution Trend over time
- Comparison between different years

![Stats Page Showing Average](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.48.00.png?raw=true)
![Stats Page Showing Comparison](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.48.11.png?raw=true)
![Stats Page Showing Trend](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.48.58.png?raw=true)


### 5. Grid Data Viewer
For users who need specific data points, this feature allows you to input an X and Y coordinate (e.g., British National Grid) alongside a pollutant and year selection. The application will return the precise pollution level at that grid reference.

![Grid Viewer](https://github.com/Nabil-1402/MINZ/blob/main/screen%20shots/Screenshot%202025-09-03%20at%2018.49.22.png?raw=true)

## Technology Stack

- **Language**: Java
- **Version Control & Collaboration**: GitHub
- **UI Styling**: CSS and JavaFX
- **Libraries**: JavaFX

## Contributors

This project was a collaborative effort by:
- Nabil Ahmed
- Mahdi Ahmed
- Muhammad Iyaad Islam
- Zakriyah Bello


Copyright (c) Michael Kölling, King's College London
