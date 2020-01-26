---
layout: page
title: Course Materials
permalink: /course-materials/
---

* [Machine vision syllabus](https://ocw.mit.edu/courses/brain-and-cognitive-sciences/9-913-pattern-recognition-for-machine-vision-fall-2004/syllabus/)
* [Download course materials](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-801-machine-vision-fall-2004/download-course-materials/)
* [An Introduction to Machine Vision Systems](https://www.thomasnet.com/articles/automation-electronics/machine-vision-systems/)
* [Reference Web 1](https://www.pyimagesearch.com/)
* [Reference Web 2](https://www.learnopencv.com/)
* [Download Open Source Computer Vision Library](https://github.com/opencv/opencv/releases)

<div style="width:100%; float: left">
    <div class="resource-pic-gallary">
<h2>reference book :</h2>
{% for resource in site.data.resources.main_resources %}
<div class="resource--image-cover-container">
            <img src="{{ resource.pic | prepend: site.baseurl }}" class="resource--image-cover">
            <p><a href="{{resource.address}}">{{resource.name}}</a></p>
        </div>
        {% endfor %}
