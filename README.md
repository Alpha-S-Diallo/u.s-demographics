verview
This project identifies which U.S. cities are most similar to Washington DC by analyzing multiple urban dimensions simultaneously. Using multi-dimensional scaling and clustering techniques, the analysis reveals patterns of similarity across firearm violence, demographics, hate crimes, and public health metrics.
What It Does
The analysis combines data from four different urban studies to create a comprehensive similarity ranking. Cities are compared across:

Firearm violence patterns
Demographic characteristics
Hate crime statistics
Public health indicators

By integrating these dimensions, the project identifies cities that share Washington DC's urban profile and reveals unexpected similarities between cities.
How It Works

Data Construction: Each city receives a similarity ranking (0-45) for each dimension, with lower numbers indicating greater similarity to DC
Multi-Dimensional Scaling: Transforms the multi-dimensional rankings into 2D space to visualize city relationships
K-Means Clustering: Groups cities with similar profiles into clusters
Heatmap Visualization: Shows the full similarity matrix across all cities and dimensions

Key Findings

Baltimore shows the strongest overall similarity to DC, particularly in firearm violence and public health
Atlanta mirrors DC's demographics and health metrics but diverges in crime patterns
Memphis has an unexpected similarity in hate crime patterns despite differences in other areas

Technologies

R with tidyverse, ggplot2, and cluster packages
RMarkdown for reproducible analysis
pheatmap for heatmap visualization
