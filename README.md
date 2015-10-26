To launch the application click on index.html in the main folder.

First i resized the application, along with minification. I also updated the js files and only call the print.css
when I'm in print mode. This achieved my goals.

Next I updated the resize pizza by splitting the style calculation and updates into different loops. This no longer
forces the composite.

Finally for optimizing the site I once again split the loop in updateLocations into two different loops one, to
calculate and the other to adjust style. I also changed the query tool to select by class instead of select all. I also
made one variable to store all the pizzas rather than keep finding them each time through the loop. I also changed
the css to use transform z. I also changed the 200 pizzas to 50, since they aren't all seen anyways.