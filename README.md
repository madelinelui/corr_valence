This is the R Markdown file for all data wrangling and results for this research project.

This project investigates whether valence in psychometric scales really matters by using the 44-item Big Five Inventory and the SELSA measure for loneliness. The raw dataset is from an unpublished dataset by Gube and Barsalou (2020).
The wrangling process includes:
  - subsetting participants from between group conditions
  - using for-loops to separate valenced items and generate a mean score per item and participant,
  - obtaining the correlation between valenced items and its p-values,
  - using patchwork to compile the visualisation
