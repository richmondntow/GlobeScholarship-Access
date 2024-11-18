# GlobeScholarship-Access
The World Scholarship Availability Map is an interactive data visualization tool built with D3.js. This map displays global scholarship availability for different countries, using color coding to highlight whether scholarships are available or not.

Features

Interactive World Map:
Displays countries color-coded based on scholarship availability.
Green for countries with scholarships, grey for those without.
Hover Tooltips:
Displays country names and scholarship availability information when a user hovers over a country.
Responsive Design:
Scalable SVG design ensures compatibility across devices and screen sizes.

Technologies Used

HTML/CSS: For the structure and basic styling of the application.
D3.js: For rendering the interactive map and managing data visualization.
TopoJSON: For handling geographic data efficiently.

How It Works

Data Mapping:
Country scholarship data is stored in a JavaScript object (scholarshipData).
Each country is identified using its ISO Alpha-3 code (e.g., "USA", "CAN").
Map Rendering:
The map is drawn using geoMercator projection for an accurate global view.
Countries are color-coded based on scholarship availability using a colorScale.
User Interaction:
Hovering over a country displays a tooltip with the country name and availability status.
Tooltips dynamically adjust their position based on mouse movement.

Dependencies

D3.js v6
TopoJSON

Contributing

Contributions are welcome! Feel free to fork the project, improve functionality, and submit a pull request.


Acknowledgments

D3.js: For enabling powerful, interactive data visualization.
TopoJSON: For efficient and scalable geographic data representation.

