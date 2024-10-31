## AIS Vessel Tracking Visualization

This application visualizes AIS (Automatic Identification System) vessel tracking data on an interactive map.

### Features
- Upload CSV files with AIS data
- Search vessels by MMSI number
- Interactive map with vessel positions
- Vessel route visualization
- Marine Traffic integration
- Zoom level indicator

### CSV File Format
The application expects CSV files with the following columns:
```
msg_type,mmsi,status,turn,speed,accuracy,lon,lat,received_time
```

Example:
```csv
msg_type,mmsi,status,turn,speed,accuracy,lon,lat,received_time
1,123456789,underway,0,12.5,1,28.9784,41.0082,2024-10-30 09:01:48.022957
```

### How to Use
1. Open the application in your browser
2. Upload a CSV file using the "Upload AIS Data" button
3. Use the search box to find specific vessels by MMSI
4. Click on vessel markers to see detailed information
5. Click on MMSI links to view vessels on Marine Traffic

### Map Features
- Black dots: Regular vessel positions
- Red dots: Vessels with multiple positions
- MMSI labels appear at zoom level 10+
- Click vessel markers to see routes and details
- Marine Traffic links in vessel popups