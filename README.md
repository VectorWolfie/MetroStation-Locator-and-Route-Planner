**MetroStation Locator and Route Planner**

The MetroStation Locator and Route Planner is a C++ program designed to assist users in finding the nearest metro station, identifying optimal routes between metro stations, and providing essential reference coordinates. The program leverages geographical data and graph algorithms to offer a comprehensive solution for metro navigation. 

**Features:**

1. **Metro Station Listing:** The program provides users with a comprehensive list of metro stations. This feature aids users in familiarizing themselves with available metro stations in the network.

2. **Route Planning:** Users can select a source metro station and a destination metro station to find the shortest route between the two points. The program employs Dijkstra's algorithm, a renowned shortest-path algorithm, to calculate the optimal route. This feature is essential for commuters seeking efficient ways to travel between different stations.

3. **Nearest Station Locator:** By entering their current geographical coordinates (latitude and longitude), users can determine the nearest metro station. The program employs the haversine formula to measure distances between coordinates, helping users identify the station that is most accessible to them.

4. **Reference Coordinates:** The program also offers a reference list of metro station coordinates. This serves as a valuable resource for users who want to cross-reference specific geographic locations with corresponding metro stations.

**How It Works:**

1. The program utilizes latitude and longitude data stored in external text files to calculate distances and create a network of metro stations.

2. Dijkstra's algorithm is employed to determine the shortest route between selected source and destination metro stations. This algorithm guarantees efficient route planning by identifying the path with the least distance.

3. The haversine formula is used to calculate distances between the user's current coordinates and the metro station coordinates, enabling the identification of the nearest metro station.

**Usage:**

1. Users can explore the list of metro stations to gain insights into available options.

2. By inputting the source and destination stations, users can obtain the optimal route for their metro journey.

3. Users can provide their current coordinates to discover the nearest metro station, simplifying their commuting decisions.

4. The reference coordinates assist users in cross-referencing geographic locations with metro stations.

**Benefits:**

- Seamlessly aids users in efficiently planning their metro routes, saving time and effort during commutes.
- Offers real-time navigation solutions by identifying the nearest metro station based on the user's location.
- Provides geographic reference data for users who want to correlate specific locations with metro stations.

In summary, the MetroStation Locator and Route Planner project offers a robust solution for metro commuters, combining route optimization, nearest station identification, and geographic reference information. This C++ program empowers users to make informed decisions when navigating urban metro networks.
