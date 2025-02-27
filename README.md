# belly-button-challenge

# Files
[Module 14 Starter Code](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/Starter_Code.zip)

# Background
In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/) which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

### Instructions

**Complete the following steps:**

1. Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

    • Use sample_values as the values for the bar chart.
    
    • Use otu_ids as the labels for the bar chart.
    
    • Use otu_labels as the hovertext for the chart.

![image](https://github.com/user-attachments/assets/42d03faf-6e2a-49eb-b463-1cbeec1733ca)

3. Create a bubble chart that displays each sample.

    • Use otu_ids for the x values.
    
    • Use sample_values for the y values.
    
    • Use sample_values for the marker size.
    
    • Use otu_ids for the marker colors.
    
    • Use otu_labels for the text values.

   ![image](https://github.com/user-attachments/assets/5b5ce973-7fac-4e51-9735-bcfd40580294)

4. Display the sample's metadata, i.e., an individual's demographic information.

    • Loop through each key-value pair from the metadata JSON object and create a text string.
    
    • Append an html tag with that text to the #sample-metadata panel.

   ![image](https://github.com/user-attachments/assets/e6d11601-98e9-42c6-ac4c-7b86ee5c2fc7)

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

   ![image](https://github.com/user-attachments/assets/4340d84f-7677-4889-869d-fc5465f0af9d)

6. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file.

    •Note: If you haven't covered GitHub Pages yet in class (as this will be introduced in Class 15.3), don't worry! As long as the finalized code is in your GitHub repository, deploying it can be done in just a few clicks. Focus on completing your app and making regular commits for now. We'll walk through the easy deployment process together in class.

### Hints

   • Use console.log inside of your JavaScript code to see what your data looks like at each step.
    
   • Refer to the Plotly.js documentationLinks to an external site. when building the plots.


