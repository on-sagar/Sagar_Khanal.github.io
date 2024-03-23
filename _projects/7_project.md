---
layout: page
title: Shake Table Fabrication
description: Mechanical Fabrication, Experimental work and Competition Organizing 
img: assets/img/Project_photos/Shake_Table.jpg
importance: 4
category: work
toc:
  sidebar: left
published: true
---

### ABSTRACT

In countries like Nepal, where funding for experimental project is very less to non-existant, there is a gap to be fulfilled for introducing low cast experimental setups that provide that missing experimental/simulating experience to college level students. In this context, me and my group of friends (being crazily interested in seismic stuff) decided in our final semesters to fabricate a low cost shaketable that would fulfill the above objectives. The final result was even better than what we intitally had in mind.We organized the first ever National level Shake Table competition using the table, got funded from Commputers and Structures Inc. (CSI) Bangkok and made it a valuable addition to the earthquake engineering classes courtesy of Assoc. Prof. Dr. Kshitij C. Shrestha (used for demonstrations to both bachelors and masters level students). Scroll down to read more. 

### THE SETUP
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shake_Table/Sketchup_figure.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sketchup model 
</div>

The Table is made up of plywood to decrease overall cost and is driven by a simple scooter motor to drive the uniaxial harmonic motion of the table. The Amplitudes can be varied from 1 cm, 2.5 cm upto 5 cm with maximum frequency upto 5 Hz and can easily support weight upto 25 Kgs without any notable deflections. The Table's frequency is controlled by the input voltage to the driving motor. The Table was further calibrated using KS48C High Sensitivity Accelerometer.

### LEARNING PROCESS
The Shake Table was immensly helpful for furthering our learning in structural dynamics. We used Bamboo sticks used in Stick food (sausafe sticks to be exact) and used hot glue to make our structures. The structures were fairly light very and had very less damping. 
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shake_Table/sensor_connection_photo.png" class="img-fluid rounded z-depth-1" %}
    </div>
        <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shake_Table/datalogger_laptop_connection.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Sensor connection on the left and Data logging system on the right
</div>

We mainly observed stiffness degradation due to incremental excitaion by studying the free vibration respones after each excitation. 

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shake_Table/Accel_time_7.png" class="img-fluid rounded z-depth-1" %}
    </div>
        <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shake_Table/Freq_Spec_7.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cropped Base Excitation offered by the Table in the left and Frequency Analysis results on the right
</div>

<div class="row mt-3">
        <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Shake_Table/Logthird_step.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Logarithmic Damping Data read from the built structure 
</div>

### SHAKE TABLE COMPETITION AT CESS-2022
The Shake Table competition at CESS-2022 was first of its kind. 20 Teams participated in the competition. All the teams were provided the base excitation and the order in which they would be excited. Click here to see the rule book and here for some of the videos.
Swipe down to see the photos



Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
