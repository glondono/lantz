---
title: Photographs
layout: page
---

## Previous Owners of the Mill
Pictures of George Adam Lantz (1788-1869), the first Lantz to own the mill (he purchased it in 1824); his son, Jacob Lantz Jr (1813-1883) who bought the mill in 1963; and William I Wilkins, who operated the mill as "Lantz Roller Mills from 1930 to 1959.

<p>
{% for image in site.static_files %}
    {% if image.path contains 'photos/HistoricPeople' %}
      {% unless image.path contains '_tn' %}
          <a href="{{site.url}}/{{ image.path }}">
            <img src="{{site.url}}/photos/HistoricPeople/{{ image.basename | append: '_tn' | append: image.extname }}" alt="">
          </a>
      {% endunless %}
    {% endif %}
{% endfor %}
</p>


## Historic Photographs of the Mill
Courtesy of Paul Stoneburner.

<p>
{% for image in site.static_files %}
    {% if image.path contains 'photos/HistoricMill' %}
      {% unless image.path contains '_tn' %}
          <a href="{{site.url}}/{{ image.path }}">
            <img src="{{site.url}}/photos/HistoricMill/{{ image.basename | append: '_tn' | append: image.extname }}" alt="">
          </a>
      {% endunless %}
    {% endif %}
{% endfor %}
</p>


## Photos of the Restoration Process - Providing Support
Railroad ties stacked as cribbing to provide structural support in the basement of the mill while the building is gently raised and leveled with hydraulic jacks.

<p>
{% for image in site.static_files %}
    {% if image.path contains 'photos/Cribbing' %}
      {% unless image.path contains '_tn' %}
          <a href="{{site.url}}/{{ image.path }}">
            <img src="{{site.url}}/photos/Cribbing/{{ image.basename | append: '_tn' | append: image.extname }}" alt="">
          </a>
      {% endunless %}
    {% endif %}
{% endfor %}
</p>

## Photos of the Restoration Process - Rebuilding the South-West Wall
The South-West addition of the mill, built in the 1920s was too rotted to save. Since it was not historically significant, it was torn down on August 25, 2007, and the original wall of the mill was rebuilt.

<p>
{% for image in site.static_files %}
    {% if image.path contains 'photos/SouthWestWall' %}
      {% unless image.path contains '_tn' %}
          <a href="{{site.url}}/{{ image.path }}">
            <img src="{{site.url}}/photos/SouthWestWall/{{ image.basename | append: '_tn' | append: image.extname }}" alt="">
          </a>
      {% endunless %}
    {% endif %}
{% endfor %}
</p>

## Restoration of the Rear Gable Wall and the Privy
June-July, 2012

## Replacing some Weatherboard on the front of the Mill
June-July, 2012

## Taking down the Century-Old Sycamore
July 2013. We finally cut-down the century-old sycamore that was growing behind the mill.  The trunk was 17 feet in circumference at the base and had grown within 2 inches of the back of the mill.  Some of the branches hanging over the mill were the size of fully grown trees and with all of the powerful storms over the past few years (yes, due to global warming - don't deny it!) we decided, much to our chagrin, that the tree had to go!

## The Mill Prior to Restoration - Inside Photographs
All photos are of the inside of the mill and were taken in April and June of 2006 prior to the beginning of the restoration process.

<p>
{% for image in site.static_files %}
    {% if image.path contains 'photos/PriorInside' %}
      {% unless image.path contains '_tn' %}
          <a href="{{site.url}}/{{ image.path }}">
            <img src="{{site.url}}/photos/PriorInside/{{ image.basename | append: '_tn' | append: image.extname }}" alt="">
          </a>
      {% endunless %}
    {% endif %}
{% endfor %}
</p>

## The Mill Prior to Restoration - Outside Photographs
All photos are of the outside of the mill and were taken in December 2006 and spring 2007 prior to the beginning of the restoration process

<p>
{% for image in site.static_files %}
    {% if image.path contains 'photos/PriorOutside' %}
      {% unless image.path contains '_tn' %}
          <a href="{{site.url}}/{{ image.path }}">
            <img src="{{site.url}}/photos/PriorOutside/{{ image.basename | append: '_tn' | append: image.extname }}" alt="">
          </a>
      {% endunless %}
    {% endif %}
{% endfor %}
</p>
