# Palmer Penguins: Data Visualization

## Objective
Turn the Palmer Penguins data into clear visual stories and explain what the charts mean in the real world.

## Dataset
Palmer Penguins dataset from seaborn-data on GitHub. It has 344 penguins and 7 columns: species, island, bill length, bill depth, flipper length, body mass, and sex. After dropping 2 empty rows and filling missing sex values with "Unknown", 342 rows were used.

## Visualizations
1. Histogram: distribution of body mass
2. Bar chart: average body mass by species
3. Box plot: flipper length by species
4. Scatter plot: flipper length vs body mass
5. Count plot: penguin count by island and species
6. Heatmap: correlation between measurements

All charts have titles, axis labels, and legends where needed.

## Key Insights
1. Gentoo penguins are the heaviest and have the longest flippers.
2. Flipper length and body mass are strongly linked (about 0.87).
3. Species live on different islands: Gentoo only on Biscoe and Chinstrap only on Dream.

## Files
- notebooks/data_visualization.ipynb: code and charts
- docs/visualization_report.pdf: explanation of each chart, insights, and real-world interpretation
