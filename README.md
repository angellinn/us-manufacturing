# Web Mapping & Smart Dashboard—The Impact of COVID-19 on U.S. Manufacturing Industry
**Author:** Angel Lin
<br>**Date:** 2020/06/05
## Background Information

### Abstract
A supply chain is a network of organizations, resources, people, and information that are involved in the process of procurement of raw materials, production of goods, shipping between warehouses and retailers, and the distribution of finished goods to end customers. Over time, the traditional supply chain practices are being challenged, pressuring leaders to come up with innovative solutions to overcome the barriers in an increasingly complex environment. Consumer behavior and technology advancement have shaped the landscape of supply chain in an unprecedented way—customers expect companies to respond faster as well as shortening delivery time; rich, informative data flows into organizations in an accelerated rate; machine learning takes over the traditional labor intensive work. In addition, the global supply chain has been highly impacted over the course of COVID-19. With more than 200 of the Fortune Global 500 firms having a presence in Wuhan, the original outbreak of coronavirus, companies need to react quickly to the disruption and focus more on building resilience, contingency plans, and risk assessment into supply chains. With all the reasons above, the industry is experiencing a transformation of physical supply chain to a digital supply network. Location intelligence, mapping and visualization tool, and real-time monitoring have become central to the digital transformation.

### GIS and Supply Chain
Geographic Information System (GIS) is a ground-breaking technology that provides tools and technologies to build a more resilient global supply chain. Since supply chain is a geographically intensive business, GIS can be very useful when it comes to mapping locations of manufacturing plants, warehouses, distribution centers, suppliers, and customers. It can also be used to analyze routes and understand operating environment around the corporate. Most importantly, GIS offers a valuable supply chain risk management tool during uncertain times. In a pandemic environment for example, risks become dynamic. Companies need visibility to the entire value chain to understand what and where the impact is, and transparency to their suppliers to manage and mitigate risks. Presenting supply chain performance data in the form of a spreadsheet ignores the real-world influence of geography on transportation. Therefore, supply chain professionals need GIS to manage massive amount of location-based or spatial data to make better decisions and strategies.

### Web Mapping
A web map is an interactive online map that displays geographic information and content organized as layers. The goal is to tell stories or answer questions through visualizing geographic spatial data. For example, this web map I created shows all the airports in the United States. This map can answer questions such as where all the airports are located at and which states have the highest total number of airports.
![airport map](img/airport.JPG)

In general, a map contains a reference basemap, a set of data layers (often include interactive pop-up windows with information about the data), map extent, and navigation tools to pan and zoom. Since a web map is hosted online, the content can be shared across different applications, users, and devices.

### Smart Dashboard
Many of the web map interfaces also come along with a smart dashboard. A dashboard is a graphical user interface that visually displays important information from multiple data sources into one place. On a web map, a smart dashboard plays the role of organizing and highlighting key information from the map. The data shown on the smart dashboard usually changes accordingly to the user’s interaction with the web map. An example of the usage of smart dashboard is the Johns Hopkins University COVID-19 Dashboard. The map provides three aspects for viewers: World Map, U.S. Map, and Critical Trends, and includes multiple smart dashboards to reflect the overall COVID-19 statistic in real time.

Both web mapping and smart dashboard are crucial analytics techniques that will help supply chains to enhance risk management strategies, increase visibility and transparency throughout the process, and stimulate responsiveness. They help organize complicated information and provide key insights to enable front-line decision making.

## Project Introduction

### Motivation
Due to COVID-19, many manufacturing plants are forced to shut down globally. In the United States, manufacturing industry accounts for 11.39% of the total output in the economy, employing 8.51% of the workforce (Source: National Association of Manufacturers). I want to create a web map that provides critical insights about how the manufacturing companies are impacted in each state.

### Systematic Architecture
External Internet
-	Basemap
-	Interactive Component
Internal Network
-	Web host (webserver)
-	Geospatial Server
-	File Server

### Code Analysis
Library used
-	Leaflet

### Data Sources
### References
