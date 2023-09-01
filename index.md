---
layout: page
title: About
description: Omid Bazangani is an Embedded Software Engineer
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap');

/* Global Styles */
body {
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
    transition: all 0.3s ease;
}

h4 {
    font-size: 26px;
    margin-top: 0;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.1);
    color: #2c3e50;
    border-bottom: 2px solid #2c3e50;
    padding-bottom: 10px;
}

a {
    color: #3498db;
    transition: color 0.3s ease;
}

a:hover {
    color: #2980b9;
    text-decoration: none;
}

/* CV and LinkedIn Links */
/* ... */
.cv-link span, .linkedin-link span {
    vertical-align: middle;
}

.cv-link, .linkedin-link {
    display: inline-block;
    padding: 5px 10px;
    border: 2px solid transparent;
    border-radius: 5px;
    transition: all 0.3s ease;
}

.cv-link:hover, .linkedin-link:hover {
    background-color: #3498db;
    color: #fff;
    border: 2px solid #3498db;
}
/* ... */


/* LinkedIn and PDF Images */
.icon-img {
    vertical-align: middle;
    margin-right: 5px;
    width: 24px;
    height: 24px; /* Explicitly set the height */
}

/* Container */
.container {
    max-width: 900px;
    margin: 40px auto;
    background-color: #fff;
    padding: 30px 40px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    border-radius: 7px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.container:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

/* Image */
img {
    max-width: 200px;
    border-radius: 50%;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    margin: 20px 0;
}

img:hover {
    transform: scale(1.1);
}
/* ... your other styles ... */

/* Prevent users from dragging the image */
img {
    pointer-events: none;
    user-drag: none;
    user-select: none;
    -moz-user-select: none;
    -webkit-user-drag: none;
    -webkit-user-select: none;
    -ms-user-select: none;
}
/* Contact Section */
.row-fluid {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    flex-wrap: wrap;
}

.span5, .span2 {
    margin: 10px 0;
}

#hide_email {
    margin-top: 20px;
}


document.addEventListener('contextmenu', function(e) {
    if (e.target.tagName === 'IMG') {
        e.preventDefault();
    }
});

</style>

Omid Bazangani is a seasoned Embedded Software Engineer with over 7 years of industry experience. He specializes in the development and optimization of embedded systems, with a keen interest in system security and integrity.

Omid earned his M.Sc. in Embedded System security, safety, and integrity in 2020 from the University of [Grenoble-INP](https://esisar.grenoble-inp.fr/). He is currently a PhD candidate at [CESCA Lab](https://cescalab.cs.ru.nl/members/) of Radboud University. His research focuses on Side-channel simulators for ARM Cortex-M microcontrollers. He is mentored by [Lejla Batina](https://www.cs.ru.nl/~lejla/) and [Ileana Buhan](https://ileanabuhan.github.io/). 

His professional journey revolves around side-channel attacks and simulators, primarily for ARM microcontrollers. He has a particular interest in microarchitectural profiling for side-channel simulator design based on machine learning algorithms.

<!-- ... -->
<a class="cv-link" href="{{ BASE_PATH }}/PDFDocs/bazangani_cv.pdf">
    <img src="../pics/pdf.png" alt="CV as PDF" class="icon-img">
    <span>Curriculum Vitae</span>
</a><br/>

<a class="linkedin-link" href="https://www.linkedin.com/in/omid-bazangani/">
    <img src="../pics/linkedin.png" alt="LinkedIn" class="icon-img">
    <span>LinkedIn</span>
</a><br/>
<!-- ... -->


<div class="container">
<h4><a name="contact"></a>Contact</h4>

    <div class="row-fluid">
        <div class="span5">
           Omid Bazangani<br/>
            <a href="https://www.ru.nl/dis/">Department of Digital Security </a><br/>
			<a href="https://www.ru.nl/over-ons/de-campus/gebouwen-en-ruimtes/mercator-i">Mercator Building</a><br/>
            <a href="https://www.ru.nl/">Radboud University</a><br/>
          
            Toernooiveld 200 <br/>
            Nijmegen<br/>
            The Netherlands<br/><br/>

            <div id="hide_email">
            &#x2709; Email: omid.bazangani@ru.nl<br/>
            &#x2709; Email: omid.bazangani@gmail.com<br/>
            &#x1F4F1; Mobile: 0642923519
            </div>
        </div>

        <div class="span2">
        <a href="../pics/omid.jpg">
            <img src="../pics/omid.jpg"
                  title="Omid Bazangani" alt="Omid Bazangani"/></a>
        </div>
    </div>
</div>