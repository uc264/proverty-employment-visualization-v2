# Improved version of Project 1 with enhanced visualization features  
# Project 1 - poverty-employment-visualization-v2 

## Overview
This project presents an interactive web application that visualizes poverty rates, employment rates, and per capita income across U.S. counties.  
It features a choropleth map and a scatterplot for correlation analysis, now enhanced with zoomable brushing and selection features.

## Data Sources
- USDA Atlas of Rural and Small-Town America
- GeoJSON: U.S. Counties shapefile

---

## Version 2 (Updated Submission)

### What I Learned
Through Project 2 and Project 3, I learned better design practices:
- Cleaner UI layouts and flexible grids
- Improving tooltip interaction with users
- Enhancing user experience with loading indicators, search functionality
- Implementing statistical analysis (correlation, deviation)
- Adding brush-based zooming and interactive multi-selection on scatterplots

---

## Goals of Resubmission
- Allow users to brush (select) regions on the scatterplot
- Enable persistent highlighting after zoom actions
- Improve scatterplot interactivity with visual feedback
- Separate single-click selection vs. multi-brush selection
- Maintain a smooth and professional user interface

---

## List of Changes

| Feature | Description |
|:--------|:------------|
| **Brush Selection on Scatterplot** | Added brush tool to allow rectangular selection of points |
| **Zoom After Brushing** | After brushing, the scatterplot automatically zooms to the selected area |
| **Persistent Highlighting** | Brushed points stay highlighted even after zooming in or out |
| **Improved Highlighting Styles** | Added distinct styles for brushed points (`highlighted`) vs selected point (`selected-point`) |
| **Zoom Controls** | Added Zoom In, Zoom Out, and Reset Zoom buttons to manually adjust scatterplot |
| **New CSS Brush Styling** | Semi-transparent blue brush selection with styled handles |
| **Code Optimization** | Simplified brush handling logic for better performance |
| **Responsive Improvements** | Brush and zoom work seamlessly across different screen sizes |
| **Enhanced County Interaction** | Clicked counties update info card, brushed selection highlights on scatterplot |

---

## Responsive Layout
- Layout switches between **single-column** (mobile/tablets) and **two-column** (desktops).
- Both choropleth and scatterplot adjust dynamically without scrollbars.

---

## Developed By
- **Umesh Chandra Nagubandi**  
- Data Source: USDA Atlas of Rural and Small-Town America

---

#  Note
This improved version focuses on **enhancing user interaction**, **data exploration**, and **visual clarity** through brushing, zooming, selection, and statistical features in scatterplots.
