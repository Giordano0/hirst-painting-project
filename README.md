\# 🎨 Hirst Painting Generator



A Python project that automates the creation of "Spot Paintings" in the style of artist Damien Hirst. This script bridges the gap between data extraction and digital art.



\## 🛠️ How it Works

1\. \*\*Color Extraction:\*\* Uses the `colorgram` library to analyze an external image (`image.jpg`) and extract a palette of RGB colors.

2\. \*\*Data Processing:\*\* Filters out background colors (like whites and greys) to keep only the vibrant tones.

3\. \*\*Automated Drawing:\*\* Utilizes the `turtle` graphics module to iterate through the color data and draw a 10x10 grid of colored dots.



\## 📊 Connection to Data Analytics

This project demonstrates a fundamental data workflow:

\* \*\*Collection:\*\* Fetching raw pixel data from an image file.

\* \*\*Cleaning:\*\* Filtering the color list to remove unwanted background noise.

\* \*\*Visualization:\*\* Representing the final dataset as a structured visual grid.



\## 🚀 Installation

1\. Clone the repository.

2\. Install the required library:

&#x20;  ```bash

&#x20;  pip install colorgram.py

