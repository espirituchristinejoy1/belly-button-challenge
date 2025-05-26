Module 14 # belly-button-challenge

## Background
Build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) 
were present in more than 70% of people, while the rest were relatively rare.


## Instructions

## Step 1
1. Create a new repository for this project called belly-button-challenge. Do not add this Challenge to an existing repository.
2. Clone the new repository to your computer.
3. Inside your local git repository, copy the files from in the StarterCode folder contained within the 
Module 14 Challenge zip file. index.html, samples.json, and the static folder.
4. Push the above changes to GitHub.
5. Deploy the new repository to GitHub Pages.


## Step 2
1. Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
3. Use sample_values as the values for the bar chart.
4. Use otu_ids as the labels for the bar chart.
5. Use otu_labels as the hovertext for the chart.


## Step 3
Create a bubble chart that displays each sample.
  - Use otu_ids for the x values.
  - Use sample_values for the y values.
  - Use sample_values for the marker size.
  - Use otu_ids for the marker colors.
  - Use otu_labels for the text values.


## Step 4
1. Display the sample's metadata, i.e., an individual's demographic information.
2. Loop through each key-value pair from the metadata JSON object and create a text string.
3. Append an html tag with that text to the #sample-metadata panel.


## Step 5
Update all the plots when a new sample is selected. In addition create any layout for the dashboard.


## Step 6
Deploy app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
