---
layout: default
---

## About Me
<tr>
    <td> <img class="profile-picture" src=""></td>
    <td><div class="profile-doc">
		CSE Undergraduate from Anna University<br>
        Interested in Software Engineering, Object-Oriented Programming, and Web Development.<br>
		<br> 
		 <a href="mailto:dhayalvignesh@gmail.com">
        <i class="fa fa-envelope" aria-hidden="true"></i> dhayalvignesh@gmail.com</a> <br> 
		<a href="https://github.com/VIGNESH-2737">
                    <i class="fa fa-github" aria-hidden="true"></i> Github </a> <br> 
		<!-- <a href="https://scholar.google.com/citations?user=9ixpc8MAAAAJ&hl=en&oi=ao">
			<i class="fa fa-google" aria-hidden="true"></i> Google Scholar </a> <br>  -->
		<a href="https://www.linkedin.com/in/aman190202/">
			<i class="fa fa-linkedin" aria-hidden="true"></i> LinkedIn </a> <br> 
			<br>
	</div></td>
</tr>

I am a CSE Undergraduate from Anna University, passionate about solving real-world problems using programming. I have worked on several projects, including a Railway Reservation System, Taxi Booking System, and Web Development and Data Science projects. I am currently improving my skills in data structures, algorithms, and software design principles.

### Updates : 
1. Currently preparing for interviews in software engineering [2024]
2. Completed my undergraduate studies in Computer Science and Engineering[2020-2024]

---
## Experience

Year | Organization | Category
2023 | AI Club CFI IITM | AI Summer School by Indian Institute of Madras[link].
2023 | Programming Club IITM | Programming Summer School by Indian Institute of Madras[link].
---

{% for jobs in year.items %}
<table class="paper-list">
  <tr>
  	{% if jobs.logo %}
    <td><img class="paper-logo" src="{{jobs.logo}}"></td>
	{% endif %}
	{% if paper.paper-logo-mp4 %}
    <td>
		<div class="paper-logo">
		<video width="80%" height="80%" muted autoplay loop>
			<source src="{{paper.paper-logo-mp4}}" type="video/mp4">
			Your browser does not support the video tag.
		</video>
		</div>
	</td>
	{% endif %}
    <td>
		<p class="paper-title">{{jobs.title}}</p>  
		<p class="paper-authors">
			{{jobs.description}}
		</p>
		<p class="paper-pub">{{paper.paper-pub}}</p>
		<p class="paper-links">
			{% if paper.link-pdf %}
			<a href="{{paper.link-pdf}}" target="_blank" rel="noopener">
				<i class="fa fa-file-pdf-o" aria-hidden="true"></i> PDF </a>
			{% endif %}

		</p>
	</td>
  </tr>
</table>
{% endfor %}
{% endfor %}


<!-- ## Publications
{% assign years = site.data.papers | group_by:"year" | sort: "name" | reverse %}

{% for year in years %}
### {{ year.name }}	
---

{% for paper in year.items %}
<table class="paper-list">
  <tr>
  	{% if paper.paper-logo %}
    <td><img class="paper-logo" src="{{paper.paper-logo}}"></td>
	{% endif %}
	{% if paper.paper-logo-mp4 %}
    <td>
		<div class="paper-logo">
		<video width="80%" height="80%" muted autoplay loop>
			<source src="{{paper.paper-logo-mp4}}" type="video/mp4">
			Your browser does not support the video tag.
		</video>
		</div>
	</td>
	{% endif %}
    <td>
		<p class="paper-title">{{paper.paper-title}}</p>  
		<p class="paper-authors">
			{% for author in paper.paper-authors %}
				{% if forloop.last == true %}
					{{author.name}}.
				{% else %}
					{{author.name}},
				{% endif %}
			{% endfor %}
		</p>
		<p class="paper-pub">{{paper.paper-pub}}</p>
		<p class="paper-links">
			{% if paper.link-pdf %}
			<a href="{{paper.link-pdf}}" target="_blank" rel="noopener">
				<i class="fa fa-file-pdf-o" aria-hidden="true"></i> PDF </a>
			{% endif %}

		</p>
	</td>
  </tr>
</table>
{% endfor %}
{% endfor %} -->

---
## Projects

<tr>
    <td><div>
	    <a href="https://github.com/aman190202/neural_fields_bvc">
            <i class="fa fa-github" aria-hidden="true"></i> 1.	Drum Kit – Interactive drum sounds with keyboard/mouse inputs.
            <br> 
            <br> 
		<a href="https://github.com/aman190202/neural_fields_bvc">
            <i class="fa fa-github" aria-hidden="true"></i> 2.	QR Generator – Generate QR codes with customization options.
            <br> 
            <br> 
		<a href="https://github.com/aman190202/neural_fields_bvc">
            <i class="fa fa-github" aria-hidden="true"></i> 3.	Band Name Generator – Generate fun band names dynamically.
            <br> 
            <br> 
		<a href="https://github.com/aman190202/neural_fields_bvc">
            <i class="fa fa-github" aria-hidden="true"></i> Neural Fields with encoding:</a> 4.	Family Tracker – Track family details with calendar and messaging.
            <br> 
            <br> 
		<a href="https://github.com/aman190202/neural_fields_bvc">
            <i class="fa fa-github" aria-hidden="true"></i> Neural Fields with encoding:</a> 5.	Permalist – CRUD app for permanent lists with API.
            <br> 
            <br> 
		<a href="https://github.com/aman190202/neural_fields_bvc">
            <i class="fa fa-github" aria-hidden="true"></i> Neural Fields with encoding:</a> 6.	Keeper App – Note-keeping app inspired by Google Keep.
            <br> 
            <br> 
	</div></td>
</tr>

<!-- ---
## Invited talks

Date | Event | Details
-----|-------|--------
April, 24th 2024 | FMX 2024  | Survey on NeRFs and 3DGS for the Lighting & Rendering track organized by [Christophe Hery](https://www.linkedin.com/in/christophehery/) in Stuttgart, Germany. Thank you all for the great time there!
May, 6th 2024 | Machine Learning Coffee Seminar | Finnish Center for Artificial Intelligence (FCAI) [talk](https://fcai.fi/calendar/2024/5/6/juho-kannala-tba) on neural rendering. -->


---
<br>
 Template Credits : <a href="https://maturk.github.io">Matias Turkulainen</a>