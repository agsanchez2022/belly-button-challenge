# Belly Button Biodiversity Dashboard

## Background
This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

## Project Overview
The dashboard allows users to:
- View a bar chart of the top 10 OTUs for a selected individual.
- Explore a bubble chart displaying all samples.
- Access individual demographic metadata.

## Getting Started

### Prerequisites
- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with D3.js for data visualization.
- A web browser to view the dashboard.

### Before You Begin
1. **Create a New Repository**:
   - Name your repository `belly-button-challenge`.

2. **Clone the Repository**:
   - Clone the repository to your local computer using:
     ```bash
     git clone https://github.com/yourusername/belly-button-challenge.git
     ```
   - Replace `yourusername` with your GitHub username.

3. **Copy Files**:
   - Inside your local Git repository, copy the files from the StarterCode folder contained within the Module 14 Challenge zip file (i.e., `index.html`, `samples.json`, and the `static` folder).

4. **Push Changes to GitHub**:
   - Add and commit your changes:
     ```bash
     git add .
     git commit -m "Initial commit with starter files"
     git push origin main
     ```

5. **Deploy to GitHub Pages**:
   - Go to your repository settings on GitHub.
   - Under the "Pages" section, select the branch (usually `main`) and save. Your site will be published at `https://yourusername.github.io/belly-button-challenge/`.

## Files
- `index.html`: The main HTML file that includes the structure of the dashboard.
- `samples.json`: The dataset containing the microbial data.
- `static/app.js`: The JavaScript file where D3.js is used to create the visualizations.
- `static/style.css`: The CSS file for styling the dashboard.

## Visualizations

### Bar Chart
- A horizontal bar chart displays the top 10 OTUs found in the selected individual.
- Uses `sample_values` as values, `otu_ids` as labels, and `otu_labels` as hover text.

### Bubble Chart
- A bubble chart visualizes all samples.
- Uses `otu_ids` for x values, `sample_values` for y values, and marker size/color.
- `otu_labels` provide text values for the bubbles.

### Sample Metadata
- Displays individual demographic information by looping through each key-value pair in the metadata JSON object.

## User Interaction
- The dashboard updates all visualizations when a new sample is selected from the dropdown menu.

## Technologies Used
- HTML
- CSS
- JavaScript
- D3.js




