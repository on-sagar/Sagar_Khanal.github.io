---
layout: page
title: Hazard Visualization Project
description: D3js, Javascript, Interactive Dynamic Data Visualization
img: assets/img/Project_photos/Earthquake_Data_Visualization.png
importance: 4
category: fun
toc:
  sidebar: left
published: true
---

### Motivation

Despite the high level earthquake hazard in Nepal, there have been relatively less efforts from the Nepali government to help visualize the earthquake hazard in the country. In this context, I wanted to create a visualization that could be used to show how frequent earthquakes are over Nepal in a way that can be comprehended by people from all backgrounds. 

### Getting the data

The earthquake data is available at the National Earthquake Monitoring and Research Center's [Website portal](https://seismonepal.gov.np/earthquakes).The page's HTML sourcecode is relatively simple which can be scraped using any webscraping packages. I used Beautifulsoup from Python. See the webscraping code [here](https://github.com/on-sagar/Viz_projects/blob/main/See_this_finalV.1.0.0/webscraping_bs4.py).

### Tools used

I used one of the most popular data visualization tools in Javascript D3js. Learning it was definately a fun yet tiring experience but the output was worth it. Through this static website, i cannot give you the full dynamic and interactive experience of the visualization that the same visualizatin on other compatible websites can offer, like [here](). But, anyways, it looks super cool and the code is available [here](https://github.com/on-sagar/Viz_projects/blob/main/See_this_finalV.1.0.0/V_1.0.0.html).

### Output
Below is the sample of using the visualization. Pull the repo above and open the code using a liver server to have the same experience. Cheers!

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/EQ_hazard_visualization_vid.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Excuse the low quality screen recording
</div>