---
name: Homework8
tools: [Python, HTML, vega-lite]
image: assets/pngs/cover.png
description: This is my homewhork8
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homehwork8： Charts of University Agency Owned Buildings

{% include assignment.html %}

The upper visualization is a bar chart that illustrates the count of buildings categorized by their usage description, when the cursor hover over on a bar, it will show each cartgory's value.This chart is able to show the usage types among university buildings and let users identify which usage types are most common.

I used bars as the mark of the chart, which is effective for showing the quantity and for comparison. The x-axis is nominal, representing agency names, and the y-axis is quantitative, representing the count of buildings. I also tilted the x-axis to a 90-degree angle to ensure they were not overlapping. I just leave the chart as the default color. There is no need to use multiple colors since they are the same quantity.


The lower visualization is a bar chart that illustrates the count of buildings categorized by their University Agency. When the cursor hover over on a bar, it will show each cartgory's value.This chart is able to show the usage types among university buildings, and let users This visualization presents a bar chart demonstrating the number of buildings each university agency owns. It allows users to quickly identify which agencies have the largest and smallest numbers of buildings.

I used bars as the mark of the chart, which is effective for showing the quantity and for comparison. The x-axis is nominal, representing agency names, and the y-axis is quantitative, representing the count of buildings. Because there are significant numerical differences in the number of buildings for different agencies, I have set the scale of the y-axis to exponential.I also tilted the x-axis to a 90-degree angle to ensure they were not overlapping. I set different agency to different color, make them easier to differentiate.





<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/weiqinghu0510/jekyll/blob/main/Workbook.ipynb" text="The Analysis" %}
</div>

