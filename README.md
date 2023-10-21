# NetVisualizationkit

### OverviewOverview

This project is a network visualization tool for Windows, built with the vis-network and d3 libraries. Users can input node and edge details, customize node colors and size , and view the network on a webpage.




### How to Use
* Start the server by running Visualizationkit.exe.
* Enter the desired port number or use the default (5002).
* Open a web browser and navigate to http://localhost:<port_number>/.
* Input node and edge data in the provided fields.
* Click on the "Visualize" button (or equivalent) to see the network visualization.

### Edge Format:
In this project, edges are represented using the following format:

```node1_ID>>node2_ID>>Edge_Label>>Edge_Style```

#### Edge Styles:
* dashed: Represents the edge with a dashed line in red color.
* dotted: Represents the edge with a dotted pattern.
