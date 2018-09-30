# D3RandomScatterplot
A Javascript D3 chart plotting 100 random coordinates

![D3 Scatterplot of 100 random numbers](https://github.com/Liveo123/D3RandomScatterplot/blob/master/d3plot.png)

    A folder named d3 containing file d3.v3.min.js (download)

    index.html : When run in a browser, it should display a scatterplot with the following specifications:

    [5 points] There should be 100 points using a rect shape that are randomly generated and placed on the plot. Each point’s x coordinate should be a random number between 10 and 250 inclusively (i.e., [10, 250]), and so is each point’s y coordinate. A point’s x and y coordinates should be independently computed.)
    [2 points] The plot must have visible X and Y axes that scale according to the generated points. The ticks on these axes should adjust automatically based on the randomly generated scatter-plot points.
    [2 points] Each rect point’s width and height will be of equivalent size.  Set each point’s width and height to the same value, between 1 and 5 inclusively, determined by the point’s x coordinate. Use a single linear scale and apply it to both width and height to map the domain of X values to the range of [1,5].
    [3 points] All points with a width greater than the average width of all scatter-plot rect points should be outlined in blue. All other points should be outlined green.  The points should use a transparent fill to enable visualization of overlapping points.
    Hint:  Modify the ‘stroke’ parameter of the rect.
    [3 points] It is often desirable to emphasize some important data points in a dataset. Accomplish this by displaying a text annotation for the point that contains the smallest y value.  The annotation should read “Min Y: <value>” where <value> is the minimum y.  If there are multiple points that contain the same minimum y value, you can pick whichever point you like to annotate.  Optional: experiment with different approaches to style the annotation text, e.g., try using different positioning settings, font-sizes, font-weights, and/or color to make it stand out.  
    Your GT username (e.g., jdoe3) should appear above the scatterplot. Also set the title tag to your GT username.
