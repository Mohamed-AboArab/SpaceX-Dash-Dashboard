## 📊 Dashboard Features

- **Launch Site Selector:** Pick any SpaceX launch site from a dropdown menu
- **Success Rate Pie Chart:** Interactive pie chart showing success vs failure percentage
- **Payload Range Slider:** Filter launches by payload mass (kg) using a slider
- **Scatter Plot:** Visualize relationship between payload mass and mission success
- **Year Range Selector:** Filter launches by specific year range

## 📁 Data Source

The data comes from SpaceX API, including all Falcon 9 launches up to 2025.  
Dataset includes: launch site, payload mass, mission outcome (success/failure), launch date.

## 🚀 Live Demo Idea

> *Note: This dashboard runs locally. Clone and run the app to interact with the visualizations.*

## How to Run Locally

```bash
git clone https://github.com/Mohamed-AboArab/SpaceX-Dash-Dashboard.git
cd SpaceX-Dash-Dashboard
pip install -r requirements.txt
python spacex-dash-app.py
