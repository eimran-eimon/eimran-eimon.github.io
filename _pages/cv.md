<style>body {text-align: justify}</style>
---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<u><a style="line-height: 1.5;" href="http://www.stuartgeiger.com/geiger-cv.pdf"><span style="color: #333333;"><span>Also available in PDF format.</span></span></a></u>
<h1 class="western" align="center"><b>Eimran Hossain Eimon</b></h1>
<p style="line-height: 1.5;" align="center"><span><b>Curriculum Vitae</b> </span></p>
<p style="line-height: 1.5;" align="center"><span><a href="http://is.gd/geiger_cites">Google Scholar</a> || <a href="https://ieeexplore.ieee.org/author/37087405667">IEEE Xplore</a></span></p>

Education
======
* **Institution**: Notre Dame College, Dhaka
    * GPA: 5.00/5.00
    * Major: Science
* **Institution**: Rajshahi University of Engineering & Technology (RUET)
    * CGPA: 3.15/4.00
    * Bachelor of Science in Engineering
    * Department: Computer Science & Engineering (CSE) 
    * Thesis: "***Superpixel Based Inter-Frame Prediction for Video Coding***"
    * Supervisors: [Dr. Ashek Ahmmed](https://scholar.google.com/citations?hl=en&user=inQobUgAAAAJ), [Dr. Shahid Uz Zaman](http://vu.edu.bd/cse/faculty-members/prof-drmd-shahid-uz-zaman) 

Work Experience
======

* **Research Assistant** (Feb 2018 - Oct 2019)
  * "Superpixel Based Inter-Frame Prediction for Video Coding"
    * `Superpixel`, `Affine Motion Model`
    * Publication: [doi:10.1109/ICAEE48663.2019.8975508](http://dx.doi.org/10.1109/ICAEE48663.2019.8975508)
  * "Classification Based Inter-Frame Prediction in Video Compression"
    * `Motion Discontinuity`, `Complex Motion Model`, `Neural Network`
    * Publication: [doi:10.1109/ICAEE48663.2019.8975416](http://dx.doi.org/10.1109/ICAEE48663.2019.8975416)
  
 
<hr>

* <ins>**Full-Stack Software Engineer**</ins> (Mar 2020 - Present)
  at ***CoKreates Limited***
  
  As part of its digitalization process, the Bangladesh government has developed Government Resource Planning (GRP), an Enterprise Resource Planning (ERP) solution of its own, to manage o ce works electronically to optimize and economize assets and expenses. GRP is consists of eleven modules. 
  From which, I have worked on the “Accounts Module”. Accounts Module is designed to manage all kinds of nancial activities records and transactions electronically to facilitate extensive search along with the generation of standard accounting reports.
  * Back-end: Java Spring Boot (Microservice Architecture)
  * Report Generation Tool: Jasper
  * Database: PostgreSQL
  * Front-end: Angular
  
* <ins>**Computer Vision Engineer**</ins> (Nov 2019 - Mar 2020)
at ***Business Accelerate BD Ltd.***

    **Project - People Counter**: 
    The primary goal of this project is to nd some useful business insight using the live CCTV feed
    of a store. Some main goals include:
    * Count the number of the person entered in and exited from the store.
    * Count the number of the person in a zone (like no. of people playing VR games).
    * Find the average time spent by a customer in a zone.
    * Generate a heatmap using customer’s trajectories.
    * Store the age, gender, and emotion of a customer when they are in a speci c zone(e.g. when they are seeing
    a new product or buying a product)
    
    I have used YOLOv3(You Only Look Once), MobilenetSSD(Single Shot Detection), Fast-RCNN for detecting
    people in real-time. And for tracking, I have used the “dlib correlation tracker”, which is based on Danelljan et al.’s
    2014 paper “Accurate Scale Estimation for Robust Visual Tracking”. I have also utilized the ”Intel OPENVINO”
    library for Age-Gender-Emotion detection.
    
    Result of my implemented models:    
     * Enter-exit count ([See Video Demo](https://drive.google.com/file/d/1CND1PB-FXwI56t-QMHTwWrBS2JkZB3fV/view?usp=sharing))
     * Age-gender-emotion detection ([See Video Demo](https://drive.google.com/file/d/1vBAifjEJNkIMvB9441E-CiQxlowZpqXb/view))
 
 
 * <ins>**Full-Stack Software Engineer**</ins> (Nov 2018 - Nov 2019)
   at ***E-Horizon IT Ltd.***
   
    Major Accomplishments:
    * Developed a system called “**Media Monitor & Archive**” for a Govt. Counter Terrorism Agency.
        * Server Environment: NodeJS
        * Back-end: PHP, JavaScript
        * Database: MySQL
        * Front-end: HTML, Bootstrap, JQuery
        
    * Developed a social networking site called “Deshi Social Connection”.
        * Server Environment: NodeJS
        * Back-end: Javascript
        * API: ExpressJS
        * Database: MongoDB
        * Front-end: HTML, Bootstrap, JQuery
    
    * Project Videos:
        * Deshi Social Connection ([See Video Demo](https://www.youtube.com/watch?v=05wj2LMp2KA))
        * JobBook ([See Video Demo](https://www.youtube.com/watch?v=xT5ZjoOEMR8))
   
Skills
======
* Java
* Python
* Docker
* JavaScript
* Computer Vision
* Video Codecs (HEVC, AVC)
* Android Application Development
* Machine Learning [(Accomplishment Certificate)](https://www.coursera.org/account/accomplishments/certificate/8UC38U2GD7F4)


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
  
Service and leadership
======
* Notre Dame Science Club.
* Notre Dame Math Club.
