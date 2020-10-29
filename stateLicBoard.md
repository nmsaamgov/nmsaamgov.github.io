---
layout: page
title: "NM Acupuncture Licensing Board"
---
{% include nmbd.html %}

*Acupuncturists* are licensed as Doctors of Oriental Medicine in the
state of **New Mexico** by the Board of Acupuncture and Oriental
Medicine pursuant to the *Acupuncture and Oriental Medicine Practice
Act*

The Board is subject to the *Open Meetings Act* and the resolution
implementing compliance with the OMA is
[here](files/nmbaom/nmbaom_oma_2020.pdf)

### Board Website

The offical website of The Board is located at  
[www.rld.state.nm.us/boards/Acupuncture_and_Oriental_Medicine.aspx](http://www.rld.state.nm.us/boards/Acupuncture_and_Oriental_Medicine.aspx)

Meeting notices can be found under the **Members and Meetings** link
on the left hand side of that site. 

## Updates And Reports

<ul>
{% for project in site.nmbaom %}
    <li>
      <a href="{{ project.url }}">{{ project.title }}</a> : {{
	  project.date | date: '%B %d, %Y' }} 
    </li>
{% endfor %}
</ul>
