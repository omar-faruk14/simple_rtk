# Simple RTK

This project leverages a Next.js-based application to provide accurate location tracking and mapping functionalities using a custom-built RTK (Real-Time Kinematic) device. The system is designed to be user-friendly, allowing for precise location data acquisition and visualization, suitable for various applications including forestry, environmental surveys, and agricultural planning.

![Project Image](/img/man2.jpeg)


## Project Overview

The RTK device, consisting of a Raspberry Pi, pocket router, and GPS system, captures accurate location data, which is subsequently sent to the Kintone platform. The application then retrieves and displays this data, offering comprehensive mapping and analysis capabilities.

### Key Features

#### Accurate Location Tracking
- **Device Composition**: The RTK device includes a Raspberry Pi, pocket router, and GPS system, providing reliable and precise location tracking.
- **High Precision**: By deploying a fixed-base RTK station, the system achieves a location accuracy within approximately 3cm.

#### Data Retrieval and Management
- **Kintone Integration**: The application connects to the Kintone platform to retrieve detailed information such as:
  - **Address Information**: Captures and displays location addresses.
  - **Comments and Status**: Shows comments and status updates associated with each location.
  - **Representative Details**: Includes information about representatives responsible for each site.

#### Mapping and Visualization

![Project Image](/img/map_view.jpg)

- **Interactive Map**: Utilizes a map interface to visually represent all tracked locations with marker systems.
- **Line Drawing and Shapefile Export**: Implements a Leaflet-based line drawing feature, allowing users to:
  - Draw boundaries or areas directly on the map.
  - Export the drawn areas as shapefiles, enabling further analysis in GIS applications.

  
![Project Image](/img/google_earth_view.jpg)

![Project Image](/img/google2.jpg)

### Applications and Use Cases
This application is designed to cater to a variety of needs, including:
- **Forestry and Environmental Surveys**: Facilitates easy measurement in challenging terrains such as inclined or forested areas, without the need for traditional, cumbersome surveying equipment.
- **Agricultural Planning**: Useful for calculating farm area and elevation differences, aiding in land preparation and management.

### Future Prospects
The system is poised for further enhancements, including:
- **Expanded Data Analytics**: Integration with additional data analytics tools to provide deeper insights.
- **User Experience Improvements**: Enhanced user interface and experience for smoother operation and data visualization.


