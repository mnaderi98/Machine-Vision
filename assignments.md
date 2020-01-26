---
layout: page
title: Assignments
permalink: /assignments/
---

<h1>تمرین سری 1
</h1>
<h2>با سلام</h2>
<h2>به پیوست موارد لازم به تمرین سری 1 ارسال می شود.</h2>
<h2>مهلت تحویل تمرین سری یک تا ساعت 23 و 59 دقیقه و 59 ثانیه روز جمعه 12 مهر است.</h2>
<a href="files/HW1 (1).zip">Download</a>
<br>
<ul id="archive">
{% for asg in site.assignments reversed %}
      <li class="archiveposturl" style="background: transparent">
        <span><a href="{{ asg.url | prepend: site.baseurl}}">{{ asg.title }}</a></span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right">
<a title="Download problems (pdf)" href="{{ asg.pdf | prepend: site.baseurl }}"><i class="fas fa-file-pdf"></i></a> 
{% if asg.attachment %}
&nbsp; <a title="Download attachments (zip)" href="{{ asg.attachment | prepend: site.baseurl }}"><i class="fas fa-file-archive"></i></a>
{% endif %}
</strong> 
      </li>
{% endfor %}
</ul>

