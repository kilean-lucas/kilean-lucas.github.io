---
layout: page
title: Microbially Influenced Corrosion
description: 
img: assets/img/projects/project_1/8_a1_01.jpg
importance: 1
category: work
related_publications: true
---

Microbially influenced corrosion is a phenomenon by which microbes create a corrosive microenvironment and this in turn leads to localized corrosion at the site of microbial colonization (also called a biofilm). This localized corrosion, often occurring at the microscopic scale or even the nanoscale, can accelerate overall corrosion within the system or metal, leading to the need to replace parts more frequently. This is the case in fuel/seawater systems found in marine ballast tanks. As fuel is consumed by ships out at sea, seawater is brought into the fuel tank to balance that lost ballast and prevent the ship from becoming unevenly balanced. Fuel and seawater do not mix, so there is minimal risk to the ship's engines as a result.

However, studies have shown that some marine bacteria (namely several species of sulfate-reducing bacteria) are capable of metabolizing components of the fuel, leading to growth of these bacteria in the ballast tank ecosystem and the formation of biofilms on the the steel walls of the tank. These biofilms as a result produce molecules that lead to the increased localized corrosion of the fuel tank, leading to higher maintenance costs in these ships.

The project that I worked on during my undergraduate research career at the Imaging and Chemical Analysis Lab at Montana State University focused heavily on understanding the molecular mechanisms that led to the increased rates of corrosion in these fuel/seawater systems. Over the course of 4 years, I developed workflows to characterize the metabolites within these microbial systems and the resulting effects found on the steel surfaces. One of the key discoveries that I made was the evidence of increased rates of localized corrosion at the site of manganese sulfide (MnS) inclusions that were present within the steel that we used as a model system. Imaging the corroded surface of the steel coupons that we exposed to the fuel/seawater environment revealed that MnS inclusions had greater rates of aggressive pitting corrosion of the steel, while the MnS itself remained untouched. This suggested that the steel within the region of these MnS inclusions had higher strain, likely leading to a better likelihood of the steel becoming involved in the corrosion byproduct formation and enhancing the overall rate of corrosion.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/project_1/1018_Front_14.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Pitting corrosion at the site of a manganese sulfide (MnS) inclusion. Relative to the bulk steel, corrosion occurs at a higher rate near the inclusion.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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
