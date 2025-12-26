### Project Overview

This project is a **group coursework** developed between **October 2025 and November 2025**.  

**Smart Green Recycling Navigator** is a data-driven, sustainability-focused project presented in **HTML format**, aiming to improve public participation in recycling in Hong Kong.

Although the city has seen an increase in public facilities and recycling points in recent years, recycling information remains fragmented and difficult for citizens to access. Key issues include unclear recycling locations, limited information on waste types, and uneven convenience across districts.

This project integrates open datasets from **data.gov.hk** to visualize recycling networks and public facilities in an accessible and user-friendly way. The system enables both citizens and planners to better understand recycling accessibility and infrastructure through interactive maps and automatically generated analytical reports.

---

### My Role

- **Concept & System Framework Design:** Developed the overall project concept, analytical logic, and system structure  
- **Interactive Map Development:** Implemented the interactive Folium-based map and spatial analysis logic  
- **HTML Report Development:** Wrote all HTML files for automated reports and visual presentation  
- **Team Leadership:** Served as team leader, responsible for coordinating team progress, reviewing, modifying, and unifying group members’ code  

I was responsible for the overall content planning, system framework, interactive map coding, and complete HTML implementation, while leading the team to ensure code consistency and integration quality.

---

### Approach & Methods

- **Data Integration & Cleaning:**  
  - Cleaned and standardized CSV datasets  
  - Unified coordinate systems by converting EASTING/NORTHING to latitude and longitude  
  - Integrated processed data into an SQLite database  

- **Query & Report Generation:**  
  - Designed aggregate, sub, and relational queries using Python’s `sqlite3` module  
  - Generated automatic analytical results and narrative HTML reports  

- **Visualization:**  
  - Created statistical charts and interactive maps using Folium  
  - Integrated all visual outputs into HTML reports with a unified green-themed interface  

---

### Key Features

- Interactive Folium-based recycling map  
- Two-way intelligent queries:
  - **Query by Facility** (e.g., MTR stations, community centers)
  - **Query by Waste Type** (e.g., plastics, glass, electronics)
- Automated HTML report generation  
- Integrated statistical charts and spatial analysis  

---

### Tools & Technologies

- **Data Source:** Hong Kong Waste Recycling Points.csv, Service Information of Public Places.csv
- **Database:** SQLite  
- **Programming:** Python (`sqlite3`)  
- **Visualization:** Folium, Matplotlib
- **Output:** Automated HTML reports  
