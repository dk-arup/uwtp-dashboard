# AIWASI Water Quality Dashboard

This is an Azure Static Web App for visualizing Urban Water Treatment Plant (UWTP) water quality compliance, using NGT and CPCB standards. It uses a CSV/Excel data file and provides an interactive map and compliance indicators for each plant.

## Features
- Upload or use default CSV/Excel data of UWTPs
- Visualize each plant on a map with compliance status for NGT and CPCB
- Toggle between NGT and CPCB compliance views
- Filter and search plants
- Export filtered data

## Data
- Place your data file in the `data/` folder (e.g., `data/ind_hydrowaste_mohua1.csv`)
- Supported columns: UWTP ID, State, Latitude, Longitude, BOD, COD, TSS, TP, TN, FC, etc.

## Compliance Criteria
- **NGT**: BOD (10), COD (50), TSS (20), TP, TN (10), FC (230)
- **CPCB**: BOD (10), COD (50), TSS (20), TP, TN (10), FC (230)
- Red color indicates non-compliance for a parameter

## Deployment
1. Fork or clone this repository
2. Push to your own GitHub account
3. In Azure Portal, create a Static Web App and link to your GitHub repo
4. Set the app location to `/` (root)

## Usage
- Open `index.html` in your browser or deploy to Azure Static Web Apps
- Upload your data or use the default file
- Use the sidebar to filter, search, and export data

---

This project is for visualization and prioritization. Please validate site-level details before issuing final administrative directions.
