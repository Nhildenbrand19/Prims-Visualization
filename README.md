# Prims-Visualization

# Abstract
The purpose of this project is to create a visualization that will represent how Prim’s MST algorithm works. It will not only show a visualization, but also allow for customizable features within the graph to allow users to better understand how this algorithm works. This visualization will be accessible on p5.js and use javascript for running the calculations. 

The library being utilized is a javascript library called p5.js, to help represent the graph. When the visualizations are initially run, a randomly generated graph will be displayed.

# Instructions:
To access the visualization, please follow the link below:

https://editor.p5js.org/Nhildenbrand19/sketches/Ou7K0Q4q9

All input files are included in the link, as well as on the SCC. To build this from scratch, with just the provided files. Please take PrimNode.js, Prims.js, index.html, sketch.js and style.css and input them into p5.js. Now to build this visualization simply click the play button at the top left of the screen. 

If you would rather run it locally navigate to the directory of the source files with your terminal program and run a local server. The easiest way to do this is by running: 
php -S 127.0.0.1:8000 
Open a browser window and navigate to http://localhost:8000 here you will find the web application.
What will be displayed on the right side of the screen is a graph consisting of 5 nodes, all with weighted edges to each other. A very unique piece of this visualization is the ability  to move nodes around the screen, while still keeping the edges and weights the same.  Notice that when you click on a node to move, the color of that node changes. You will also see an intro to our visualization above this, along with a number of different boxes and buttons that can be used to customize the graph. 

The first box you see labeled “Number of Nodes”, allows you to input a specific number of nodes, up to 15, and hit the button, “Generate Graph”, to create a new graph with your specified number of nodes. Again all nodes will have weighted edges to the other nodes in the graph.

The next button you see is “Add new node”. This will add a new node to the already generated graph.This allows for a bit more freedom, as more than 15 nodes can be added. 

Finally, the last three boxes you see “Starting Node”, “Ending Node”, and “New Weight” , have very nice functions. They can be used in two different ways. The first being updating a current weight in the graph with a new weight, going from the specified start node to end node. The other way this can be used is after adding a new node to the graph, connecting this node, to a node of your choice and specifying that weight. To implement this, simple click the “Update/Create Edge” button.

Lastly, and most importantly we have the “Get MST” button and “Next” button. Get MST highlights all the nodes in the graph that are included in the MST, which will be all nodes. The next button allows you to iterate through and see each edge being highlighted that is included in the minimum spanning tree according to Prim’s algorithm. 

