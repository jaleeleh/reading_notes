## chart js
 * it's easy to get started with Chart.js. All that's required is the script included in your page along with a single ```<canvas> ```node .like ```<canvas id="myChart" width="400" height="400"></canvas>```
* Chart.js is available under the MIT license.

## canvas API:
* the ```<canvas>``` element has only two attributes, ```width ```and ```height.```
he ```<canvas>``` element differs from an ```<img> ```tag in that, like for ```<video>, <audio>```, or ```<picture>``` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it,just insert the alternate content inside the ```<canvas>``` element
* The ```<canvas>``` element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context.like:```var ctx = canvas.getContext('2d');```
* Scripts can also check for support programmatically by testing for the presence of the getContext() method.
var canvas = document.getElementById('tutorial');
if (canvas.getContext) {
  var ctx = canvas.getContext('2d');
  // drawing code here
} else {
  // canvas-unsupported code here
}
* The script includes a function called ```draw()```, which is executed once the page finishes loading.

**Droawding shapes**
Unlike SVG, ```<canvas>```only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths.
```fillRect(x, y, width, height)```  Draws a filled rectangle.
```strokeRect(x, y, width, height)``` Draws a rectangular outline.
```clearRect(x, y, width, height)``` Clears the specified rectangular area, making it fully transparent

**Droawding paths**
```beginPath()```
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
```closePath()```
Adds a straight line to the path, going to the start of the current sub-path.
```stroke()```
Draws the shape by stroking its outline.
```fill()```
Draws a solid shape by filling the path's content area.

**Droawding lines**
For drawing straight lines, use the lineTo() method.
lineTo(x, y)

**Arcs**
To draw arcs or circles, we use the arc() or arcTo() methods.