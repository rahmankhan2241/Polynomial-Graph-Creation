
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Polynomial Graph Plotter</title>
</head>
<body>

<h1>Polynomial Graph Plotter</h1>

<p>This project allows users to dynamically create and plot polynomial functions of varying degrees with user-defined coefficients and intercepts. The graph shows the polynomial curve along with the minimum and maximum points, annotated with their respective coordinates.</p>

<h2>Features</h2>
<ul>
    <li>Supports polynomials of any degree (e.g., linear, quadratic, cubic, etc.).</li>
    <li>Interactive input for coefficients of each term.</li>
    <li>Displays the equation of the polynomial on the graph.</li>
    <li>Annotates minimum and maximum points on the curve with coordinates.</li>
</ul>

<h2>Requirements</h2>
<p>To run this project, ensure you have the following installed:</p>
<ul>
    <li>Python (3.6 or later)</li>
    <li>Matplotlib</li>
    <li>NumPy</li>
</ul>

<h2>Installation</h2>
<pre>
<code>pip install matplotlib numpy</code>
</pre>

<h2>Usage</h2>
<ol>
    <li>Clone the repository or download the script.</li>
    <li>Run the script using Python:</li>
</ol>

<pre>
<code>python polynomial_graph_plotter.py</code>
</pre>

<p>When prompted, enter the coefficients for each degree of the polynomial (or leave it as 1 by default). The program will plot the polynomial graph within the specified X range.</p>

<h3>Example</h3>
<pre>
<code>
# Run the function with degree 3 (cubic polynomial)
polynomial_graph(3)
</code>
</pre>

<h3>Parameters</h3>
<ul>
    <li><strong>degree</strong>: The degree of the polynomial (default is 2).</li>
    <li><strong>intercept</strong>: The y-intercept of the polynomial (default is 0).</li>
    <li><strong>X_lim</strong>: A tuple specifying the range of X values to display (default is (-10, 10)).</li>
</ul>

<h2>Code Structure</h2>
<p>The main function <code>polynomial_graph()</code> includes the following steps:</p>
<ol>
    <li>Accepts user input for polynomial degree and coefficients.</li>
    <li>Calculates and constructs the polynomial equation.</li>
    <li>Finds and annotates the minimum and maximum points on the graph.</li>
    <li>Plots the polynomial curve with formatted labels and titles.</li>
</ol>

<h2>Customization</h2>
<p>You can adjust the following parameters within the code:</p>
<ul>
    <li><code>s</code> parameter in <code>plt.scatter()</code> to increase or decrease the size of points.</li>
    <li><code>X_lim</code> to set custom x-axis limits.</li>
    <li>Offsets in <code>plt.text()</code> to position annotations.</li>
</ul>

<h2>Example Output</h2>
<p>Here’s a sample output of the polynomial graph plotter for a cubic polynomial:</p>
<p align="center">
    <img src="https://github.com/rahmankhan2241/Polynomial-Graph-Creation/blob/main/exampleGraph.png" alt="Polynomial Graph Example" width="500">
</p>

<h2>Contributing</h2>
<p>Contributions are welcome! If you have ideas for improvement, please fork the repository and submit a pull request.</p>



</body>
</html>
