---
layout: page
title: <b>B</b>ike <b>R</b>ecovery <b>A</b>nd <b>S</b>ecurity <b>S</b>ystem
description: A novel bicycle security approach using an alarmed U-lock integrated via Bluetooth to a GPS tracker. 
img: assets/img/BRASS Bike and lock.jpg
importance: 1
category: work
---
<!--
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
-->
The goal of the Bike Recovery And Security System (BRASS) project is to improve upon the designs of existing bicycle security solutions by creating a system that not only deters theft but also provides aid in the process of recovering a stolen bicycle. This can be done by looking at current solutions and choosing various components to combine into one product. Looking at Figure 1.2 shows that U-locks are the most common type of bicycle lock, while also having one of the lowest rates of stolen bicycles. However, a U-lock is a purely mechanical design that does not assist in recovering a bicycle once it is in the thief’s possession. Furthermore, mechanical locks offer no way to alert the user that their bicycle is being stolen. While an alarmed lock certainly has the potential to alert the user of bicycle theft when it occurs, it is still unable to assist the user with recovering the bicycle once the thief has it in their possession. Existing onboard GPS trackers are a great way for a user to track the location of a stolen bicycle, but lack preventative measures. Both of the existing solutions have clear pros and cons.

The BRASS solution aims to marry two different pre-existing concepts of bicycle security into one cyber-physical security system. This cyber-physical system combines the theft deterrent properties of alarmed locks with the recovery capabilities of GPS trackers. The BRASS solution consists of an alarmed U-lock that is wirelessly paired to a GPS tracking system that is mounted to the bicycle. This will satisfy the needs of any cyclist looking for both a bicycle lock and tracker by offering the key advantages of both solutions. The first advantage is that the user and those near the bicycle theft become aware that bicycle theft is in progress due to the alarmed lock. Since users are not always in the immediate vicinity of their bicycle when the theft is occurring a remote solution is provided via the GPS tracker. The tracker not only provides the user with the bicycle’s current location but if that user cannot hear the alarm they will receive an alert of the theft. This is done by connecting the alarmed lock wirelessly to the GPS tracker, allowing the two systems to communicate their status with one another. Finally, the unified system would provide the user with a proof of ownership and evidence that a theft has occurred. 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
