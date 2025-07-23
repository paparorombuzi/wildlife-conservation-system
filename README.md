# Wildlife Dashboard Project 🌿🐾

## Overview
The Wildlife Dashboard Project is an interactive platform for visualizing wildlife and environmental data. It provides dynamic maps, charts, and data tables to monitor plant biodiversity, deforestation events, and animal migration routes—all in one place.

## Features 🚀
- **Interactive Map**: Visualize plant markers and migration routes using Leaflet.js.
- **Dynamic Charts**: Explore biodiversity trends and plant distribution through responsive charts.
- **Data Tables**: Analyze raw data with integrated, user-friendly tables.
- **KPI Cards**: Get instant insights into key metrics like total plant species, endangered species, biodiversity index, deforestation events, brightness levels, and fire radiative power (FRP).

## Installation 🛠️

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/oscarmwangangi/wildlife.git
 

2. **Install Python Dependany**
```bash
pip install -r requirements.txt
```
3. **Make database Migrations**
```bash
  python manage.py makemigrations
  python manage.py migrate
  ```
4. **Install Node.js Packages**
```bash
  cd wildlife-frontend
  npm install
```
5. **Run the Frontend Application**
```bash
  npm start
```
6. **Run the Backend Application**
```bash
  python manage.py runserver
```
## Project Structure 📂
```markdown
├── wildlife_conservation                # Python backend 
│   ├── requirements.txt   # Python dependencies
│   └── WildlifeApp        # Django App
|   |___ manage.py
|   |___ README.md
    ├── Wildlife-frontend             
        │   ├── src
        │   │   ├── components     # React components (Map, Charts, DataTable, etc.)
        │   │   ├── pages          # Application pages
        │   │   └── ...
        │   └── package.json       # Node.js dependencies
        └── README.md              # This file
        ```
