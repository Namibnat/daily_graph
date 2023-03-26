# Matplotlib Cheatsheet

## Important Matplotlib.pyplot (plt) Methods

1. **plt.plot(x, y, fmt, **kwargs)**: Plots a line graph or data points with optional formatting (e.g., color, linestyle, marker).
   - x: array-like, x-coordinates of the data points
   - y: array-like, y-coordinates of the data points
   - fmt: optional string, a format specifier for color, marker, and linestyle

2. **plt.scatter(x, y, s=None, c=None, marker=None, **kwargs)**: Plots a scatter plot of x versus y with varying marker size and/or color.
   - x: array-like, x-coordinates of the data points
   - y: array-like, y-coordinates of the data points
   - s: scalar or array-like, size of markers
   - c: color, sequence, or sequence of colors
   - marker: optional string, marker style

3. **plt.bar(x, height, width=0.8, bottom=None, **kwargs)**: Creates a bar chart.
   - x: sequence of scalars, x-coordinates of the bars
   - height: scalar or array-like, heights of the bars
   - width: scalar or array-like, width of the bars
   - bottom: scalar or array-like, y-coordinate(s) of the bars' bases

4. **plt.hist(x, bins=None, range=None, density=None, **kwargs)**: Plots a histogram of a dataset.
   - x: array-like, input data
   - bins: int or sequence, number of bins or bin edges
   - range: tuple, lower and upper range of the bins
   - density: bool, if True, the histogram will be normalized

5. **plt.xlabel(xlabel, fontdict=None, labelpad=None, **kwargs)**: Sets the x-axis label.
   - xlabel: str, label text
   - fontdict: dict, optional, a dictionary controlling the appearance of the label text
   - labelpad: float, optional, spacing between the label and the x-axis

6. **plt.ylabel(ylabel, fontdict=None, labelpad=None, **kwargs)**: Sets the y-axis label (similar arguments to plt.xlabel).

7. **plt.title(label, fontdict=None, loc=None, pad=None, **kwargs)**: Sets the title of the plot.
   - label: str, title text
   - fontdict: dict, optional, a dictionary controlling the appearance of the title text
   - loc: str, optional, location of the title (default is 'center')
   - pad: float, optional, spacing between the title and the plot

8. **plt.legend(*args, loc=None, **kwargs)**: Adds a legend to the plot.
   - *args: a list of labels or a list of artists with labels
   - loc: str or int, the location of the legend

9. **plt.xlim(left=None, right=None, emit=True, auto=False, *, xmin=None, xmax=None)**: Sets the x-axis limits.
   - left: scalar, optional, left xlim
   - right: scalar, optional, right xlim
   - Other arguments control the behavior of the limits

10. **plt.ylim(bottom=None, top=None, emit=True, auto=False, *, ymin=None, ymax=None)**: Sets the y-axis limits (similar arguments to plt.xlim).

11. **plt.xticks(ticks=None, labels=None, **kwargs)**: Sets the x-axis tick locations and labels.
   - ticks: array-like, optional, a list of positions at which ticks should be placed
   - labels: array-like, optional, a list of labels to place at the given tick locations

12. **plt.yticks(ticks=None, labels=None, **kwargs)**: Sets the y-axis tick locations and labels (similar arguments to plt.xticks).

13. **plt.grid(b=None, which='major', axis='both', **kwargs)**: Configures the grid lines.
   - b: bool, optional, whether to show the grid (True) or hide it (False)
   - which: {'major', 'minor', 'both'}, optional, the grid lines to apply the changes on
   - axis: {'both', 'x', 'y'}, optional, the axis to apply the changes on

14. **plt.savefig(fname, dpi=None, bbox_inches='tight', **kwargs)**: Saves the current figure to a file.
   - fname: str or path-like object, the filename (including the file extension)
   - dpi: int, optional, the resolution of the saved image in dots per inch
   - bbox_inches: str or `matplotlib.transforms.Bbox`, optional, bounding box in inches

15. **plt.show(**kwargs)**: Displays the current figure in a separate window (useful for non-interactive environments, like scripts).


## Credit

Information provided by the fantastic 🤖 ChatGPT from OpenAI, your friendly AI language model. 🚀