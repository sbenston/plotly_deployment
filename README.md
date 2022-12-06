# Belly Button Diversity

## Overview of Project

A web dashboard created using HTML with Bootstrap stylings and charts generated with the Plotly library in JavaScript about the bacteria cultures found in anonymized volunteers' belly buttons. The first plot given is a bar chart of the top 10 bacteria cultures found in that test subject's navel, with the unique Operation taxonomical unit ID numbers used to label the y-axis against the total number found; hovering over a bar reveals the entirety of the OTU label for the culture. Next is a bubble plot that also visualizes the amount found of each culture by the relative size of each marker but does so for all cultures found for the test subject and also uses hover text to report the OTU label. Also given is a gauge that reports the frequency each volunteer washed their belly buttons in a week. A selection box is provided to change the information and charts to a different test subject.

The D3 library is used to make changes to the webpage document as well as load the sample data from a JSON file; all transformations of the data for the purposes of plotting were done with simple array operations such as the map and slice JavaScript functions. 
