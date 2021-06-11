---
layout: page
title: Home
nav_order: 1
description: >-
    A week-to-week description of the content covered in the course.
---

# Introduction to Computational Thinking with Data 📊
{: .mb-2 }
UC Berkeley, Summer 2021
{: .mb-2 .fs-6 .text-grey-dk-000 }

{: .mb-2 }
**Instructors:** Isaac Merritt (<a>isaacmerritt@berkeley.edu</a>), Ian Castro (<a>castro.ian@berkeley.edu</a>)
{: .mb-0 .fs-5 .text-grey-dk-000 }

{: .mb-3 }
**Lecture:** MW 10-11AM, TuTh 10AM-12PM, **Lab:** MW 11AM-12PM, **Discussion:** F 10AM-12PM, **Office Hours:** See [Ed](https://edstem.org/us/courses/3251/discussion/20190){:target="_blank_"}
{: .mb-0 .fs-4 .text-grey-dk-000 }

<!-- {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div> -->

[Zoom links](https://edstem.org/us/courses/6639/discussion/484638){:target="_blank_"}{: .btn .btn-purple } [Lecture recordings](https://edstem.org/us/courses/6639/discussion/484640){:target="_blank_"}{: .btn .btn-blue }

The following breakdown is tentative. All assignments are available for public consumption on our [GitHub](https://github.com/data-6-berkeley/su21){:target="_blank_"}.

{% for module in site.modules %}
{{ module }}
{% endfor %}
