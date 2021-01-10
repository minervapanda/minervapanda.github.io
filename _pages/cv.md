---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech. in Computer Science and Engineering, IIIT Bhubaneswar, 2018

Work experience
======
* Research Assistant, Niramai Health Analytix (2018 - Present)
  * Developed a multi-view convolutional neural network based architecture to detect abnormality on follow up patients with single breast (mastectomized patients) [in clinical trial involving 3000 patients]
  * Built an image processing module for automatic axilla detection from multiple views of upper body thermal images. [Patent Pending]
  * Performed hotspot segmentation for lymph node breast cancer detection using adaptive fusion temperature thresholding and malignancy classification using AdaBoost algorithm which resulted in 100% specificity and 75% sensitivity. The pilot study is submitted to Global Breast Cancer Conference 2021. 
  * Developed a novel explainability technique to score thermal breast image features by mapping to a discrete severity scale and enhanced model interpretability for a domain expert. [Patent Pending]
  * Developed a novel metric to evaluate the sensitivity and specificity of feature discretization algorithm by sub-grouping subjects into two classes on the basis of discrete scores derived. [algorithm in production]  
  * Developed a multi-view based architecture for mass detection in digital mammograms for enabling multi-modal analysis of breast cancer [currently part of pilot study]
  
* Research Intern, GVCL Lab at E-Health Research Centre 
  * IIIT Bangalore
  * Duties included: Geocoded patient addresses, built a dashboard for visualizing patient records, implemented map overlay functionality for integration with external datasets and designed a user interaction study
  * Supervisor: Professor Jaya Sreevalsan Nair
  
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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* As a Women TechMakers Lead at Google Developers Bhubaneswar from Jan 2016 to Jun 2018, I collaborated with the developers community in Bhubaneswar to ensure a diverse and inclusive environment by organizing technical meetups, mentorship sessions, talks and hackathons for women. Lead and organized the largest gathering of technical women in Bhubaneswar with 500 participants on Women's Day through the WTM program. For these outreach activities, I was sponsored by Google for travel and conference tickets to attend the I/O 2018 Conference held at Mountain View, California
