# belly-button-challenge
Instructions
Complete the following steps:

Use the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dla-1-2/m14/lms/starter/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.


Bar Chart
<img width="452" alt="image" src="https://github.com/user-attachments/assets/5db55fc5-d405-423f-a661-32429bd4fa2c">






Create a bubble chart that displays each sample.

<img width="635" alt="image" src="https://github.com/user-attachments/assets/c5705839-bd50-499e-8f46-0bd52e966593">


Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

Bubble Chart

Display the sample's metadata, i.e., an individual's demographic information.
Loop through each key-value pair from the metadata JSON object and create a text string.

<img width="635" alt="image" src="https://github.com/user-attachments/assets/c3a272ca-7320-4bb0-aec6-689699d7b980">


Append an html tag with that text to the #sample-metadata panel.

hw

Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
hw

<img width="830" alt="image" src="https://github.com/user-attachments/assets/cbcab3a0-5596-4778-8804-7d575de0f472">






Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
Hints
Use console.log inside of your JavaScript code to see what your data looks like at each step.

Refer to the Plotly.js documentationLinks to an external site. when building the plots.
