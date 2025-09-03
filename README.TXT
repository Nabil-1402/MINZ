# London Pollution Visualiser

A Java-based desktop application developed as a group project to visualise and analyse air pollution data across London. This tool provides an interactive map and data views to explore levels of various pollutants from 2018 to 2023.

## Features

### 1. Welcome Screen
The application starts with a welcoming interface that guides users to the main functionalities. By clicking the buttons in the middle of the window it explains what each application in the programme does.
![Welcome Screen](images/welcome_screenshot.png) 


### 2. Main Navigation
From the welcome window, users can seamlessly navigate to the three core parts of the application:
- **Map Visualiser**: View pollution data on an interactive map.
- **Pollution Statistics**: Analyse trends and get aggregated data.
- **Grid Data Viewer**: Query specific coordinates for precise pollution levels.

![Main Navigation](images/navigation_screenshot.png)

### 3. Interactive Map Visualiser
The core feature of our application allows for dynamic exploration of pollution data.

- **Select a Pollutant**: Choose from NO₂, PM10, or PM2.5 via a drop-down menu.
![Pollutant Dropdown](images/pollutant_dropdown.png)

- **Select a Year**: Choose a year from 2018 to 2023 to view historical data.
![Year Dropdown](images/year_dropdown.png)

- **Visualise on Map**: Once a pollutant and year are selected, the map updates to display colour-coded pollution levels across London.
![Map Visualization](images/map_visualization.png)

- **Click for Details**: Click on any data point on the map to see the exact pollution level for that location.
![Map Click Details](images/map_click_details.png)

- **Filter By Pollution Level**: by chosing from the filter drop down menu you can filter which level of pollution is shown on the map
![Filter Drop Down] (image)
![Filtered Map View] (image)



### 4. Pollution Statistics
This section provides analytical tools to understand the data better. Users can select a year and pollutant to view:
- Average Pollution
- Highest Pollution
- Pollution Trend over time
- Comparison between different years

![Stats Page Showing Average](images/stats_page.png)
![Stats Page Showing Comparison](image)
![Stats Page Showing Trend] (image)


### 5. Grid Data Viewer
For users who need specific data points, this feature allows you to input an X and Y coordinate (e.g., British National Grid) alongside a pollutant and year selection. The application will return the precise pollution level at that grid reference.

![Grid Viewer](images/grid_viewer.png)

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
