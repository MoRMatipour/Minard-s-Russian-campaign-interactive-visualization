# Minard Russian Campaign Interactive Visualization

## Introduction

This project redesigns a well-known historical information graphic using modern interactive visualization tools. The purpose of the project is not to replace or improve the original visualization, but to explore how contemporary technologies and interaction techniques can reveal new perspectives and make historical data more engaging for modern audiences.

The project focuses on the famous Russian campaign visualization created by Charles Joseph Minard, which illustrates the dramatic losses of the French army during the French invasion of Russia led by Napoleon Bonaparte. Minard’s graphic is widely considered one of the greatest examples of information design because it successfully combines multiple variables such as geography, army size, time, and temperature into a single powerful visual narrative.

In this project, the original visualization is reinterpreted using modern interactive visualization tools. The goal is to transform a classic static graphic into an interactive exploratory experience that allows users to engage with the data more actively. By combining mapping, animation, and interactive dashboards, the project demonstrates how historical data storytelling can be adapted for contemporary analytical environments.

This work also reflects a personal interest in historical events and how geography, weather, and logistics can influence major outcomes. Napoleon’s campaign in Russia represents one of the most dramatic examples of how these factors can shape the fate of an army, making it a compelling subject for data-driven storytelling.

![Original Minard Map](https://raw.githubusercontent.com/MoRMatipour/Minard-s-Russian-campaign-interactive-visualization/refs/heads/main/Images/download.jfif)

Minard’s famous map visually represents the size of Napoleon’s army as it advanced toward Moscow and then retreated during the winter of 1812.
The width of the band shows the number of soldiers remaining at each stage of the campaign, while additional elements display geographic location and temperature during the retreat. This visualization is widely regarded as one of the most powerful examples of data storytelling in the history of information design.

## Project Idea and Goals

This project redesigns the famous historical visualization created by Charles Joseph Minard, which illustrates the dramatic losses of the French army during the French invasion of Russia led by Napoleon Bonaparte. Minard’s original graphic is widely recognized as one of the most influential examples of data storytelling, as it combines multiple variables such as geography, army size, time, and temperature within a single visual narrative.

### Design Philosophy

The goal of this project was not to replace or improve the original visualization, but rather to reinterpret it using modern interactive visualization tools while preserving its historical authenticity. One of the most important design decisions was to keep the original dataset unchanged. No additional data was introduced, and the visualization was reconstructed using only the information present in the original graphic.

This approach ensures that the historical integrity of the data is preserved while allowing the visualization to be explored using contemporary analytical tools.

### Objectives of the Redesign

The redesign focuses on translating a classic static visualization into an interactive analytical experience. While the original graphic presents the entire story within a single static image, modern visualization environments allow users to interact with the data and explore different aspects of the narrative.

The main objectives of the redesign were:

- Transform the original static graphic into an **interactive visualization experience**
- Preserve the **original dataset and historical narrative**
- Enable users to **explore relationships between geography, time, and army size**
- Demonstrate how **modern visualization tools can reveal new perspectives** within historical data

### Project Purpose

Overall, the project aims to bridge historical information design with modern data visualization practices. By transforming Minard’s classic map into an interactive format, the project demonstrates how historical visualizations can be adapted for contemporary audiences while maintaining their original meaning and data structure.

## Data Reconstruction

To begin the redesign process, the original visualization created by Charles Joseph Minard was carefully studied to extract the data embedded within the map. Since the original visualization is a static graphic, the underlying dataset is not directly available in a structured format.

To address this, the data was **manually reconstructed** by identifying and recording the key variables represented in the original visualization.

### Extracted Variables

The reconstructed dataset includes the following variables:

- Latitude  
- Longitude  
- Date  
- Temperature  
- Army size  
- City locations  
- Direction of movement (Advance toward Moscow or Retreat)

### Data Preparation

After extracting the information from the original map, the data was organized into a structured **CSV dataset**. This dataset serves as the foundation for building the interactive visualizations developed in this project using Power BI and Flourish.

### Dataset Preview

Below is a preview of the reconstructed dataset used in this project.

![Reconstructed Dataset Preview](https://github.com/MoRMatipour/Minard-s-Russian-campaign-interactive-visualization/blob/main/Images/Screenshot%202026-03-13%20205403.png?raw=true)

You can access the full dataset here:  
[View the CSV Dataset](https://github.com/MoRMatipour/Minard-s-Russian-campaign-interactive-visualization/blob/main/Data/french%20marsh%20to%20russia.csv)
