# belly-button-challenge
This project creates an interactive dashboard to visualize bacteria cultures from various samples collected by the Mars rover. The dashboard uses D3.js and Plotly.js to dynamically update and display charts and metadata based on the selected sample.
Project Deliverables:
Metadata Panel: Display metadata information for each sample.
Bubble Chart: Visualize the number of bacteria per sample.
Bar Chart: Show the top 10 bacteria cultures found in each sample.
Dynamic Dropdown: Allow users to select different samples and update the dashboard accordingly.

STEPS
Include Required Libraries and ensure that D3.js and Plotly.js libraries are included in your HTML file
Place the following JavaScript code in a file named app.js
buildMetadata that Fetches and displays the metadata of the selected sample.
buildCharts that Fetches the sample data and builds both a bubble chart and a bar chart and also the init: Initializes the dashboard by populating the dropdown menu and displaying data for the first sample.
optionChanged: Updates the dashboard when a new sample is selected from the dropdown menu.
T o view the chart, open index.html in your browser.
Use the dropdown menu to select different samples.
Observe the metadata panel and the charts updating dynamically based on the selected sample.
