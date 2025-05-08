# Jupyter notebook: Anscombe's Quartet Visualization

A visualization of Anscombe's Quartet using Jupyter notebook and matplotlib in the style of Edward Tufte [The Visual Display of Quantitative Information](https://www.edwardtufte.com/book/the-visual-display-of-quantitative-information/).

## What is?
[Anscombe's Quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet) is a classic statistics demonstration that shows how valuable it is to visualize data, even when its statistical properties appear similar, or in this case, identical.

All four datasets in the quartet have the following properties (but a very different distribution, once plotted):

- N = 11
- mean of X's = 9.0
- mean of Y's = 7.5
- equation of regression line: Y = 3 + 0.5X
- standard error of estimate of slope = 0.118
- t = 4.24
- sum of squares X – X̄ = 110.0
- regression sum of swuares = 27.50
- residual sum of quares of Y = 13.75
- correlation coefficient = .82
- r² = .67

## But why?
I am interested in the comparitive ability of various statistics and data visualization frameworks to load data and visualize (and customize!) graphs. I am starting with Jupyter notebooks, and plan to continue to other approaches, such as D3 and more out-of-the-box SaaS products such as Tableau.

I started with this simple dataset because the last time I tried something like this, it was _deceptively difficult_ to achieve the level of typographic display customization I was after.

## Requirements
- Python 3.7+
- pandas
- matplotlib
- seaborn

## Usage
Open the `anscombe_visualization.ipynb` file in Jupyter Notebook or Jupyter Lab.

## Preview

<img src="preview.png" width="600" alt="Anscombe's Quartet Visualization">

You can view the [full notebook here](anscombe_visualization.ipynb).