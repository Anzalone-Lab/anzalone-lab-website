---
---

# Welcome to the Clinical informatics for Analytics and Translation (CAT) Lab

The Clinical informatics for Analytics and Translation (CAT) Lab is dedicated to advancing the use of real-world clinical data to improve health outcomes and reduce disparities, particularly in rural and underserved populations. Our work sits at the intersection of clinical informatics, data science, and population health.

We specialize in the secondary use of electronic health record (EHR) data, supporting large-scale observational studies and multisite collaborations. Our research emphasizes reproducibility, data quality, and methodological rigor across complex, heterogeneous healthcare data sources.

The lab plays an active role in national research initiatives, including PCORnet, the National Clinical Cohort Collaborative, All of Us, Cosmos, and TriNetX, where we contribute to data standardization, governance, and cross-site analytics. We develop scalable approaches to cohort identification, data harmonization, and outcome modeling that support both research and real-world decision-making.

Our work is particularly focused on:
- Understanding rural–urban disparities in health outcomes  
- Developing interoperable data infrastructure and standards  
- Applying advanced statistical and machine learning methods to clinical data  
- Supporting equitable and transparent use of health data in research  

Based at the University of Nebraska Medical Center, the lab collaborates with clinicians, researchers, and public health partners to translate data into meaningful improvements in care and policy.

## This site is a work in progress!

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
