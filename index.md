---
title: Home
---

# Toward a better understanding and management of brain ageing

My research project focuses on the role of intracranial vessel pulsation in neurodegenerative diseases. 

Worldwide, more than 50 million people have dementia, meaning they have severe cognitive alterations that reduce their independence in daily life activities. However, in most cases, no cure exists. 

I belive that mathematics and physics combined with measurements of intracranial fluid dynamics can help to better understand and characterise brain ageing. Ultimately it will provide new, outside-the-box, diagnostic approaches relevant for both preventive strategies and patient follow up.


{% include section.html full=true %}

{% include banner.html image="images/banner.png" %}

{% include section.html %}

# Highlights

{% capture text %}
  Recently, new fluid flow pathways have been discovered around blood vessels in the brain. We are showing that brain waste and nutrient transport through those pathways are strongly affected by vessel pulsatility. This opens a new avenue of understanding of brain physiology. In particular, we  show that specific wave pattern during sleep might be a key process for healthy brain clearance.

  Image from [Mestre et al.]("https://www.nature.com/articles/s41467-018-07318-3")


{%
  include link.html
  link="_posts\2023-03-03-naturecomms.md"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/particle_tracking.gif"
  link="research"
  title="Effect of intracranial pulsatility on brain clearance"
  text=text
%}

{% capture text %}

Describing the coupling between cerebral vessels and the surrounding tissues necessitates complex multi-physics multi-scale modeling tools which we are developing and validating. The brain tissue is represented as a deformable poroelastic medium where the cells are the solid part and the interstitial fluid is the fluid part. The vascular network is represented as a network of 1D pipes. 


{%
  include link.html
  link="tools"
  text="Read mode"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/modeling.png"
  link="resources"
  title="Fluid - poroelastic interaction modeling"
  flip=true
  text=text
%}

{% capture text %}

We are developping new medical technologies to assess brain fluid dynamics in-vivo for diagnosis and patient follow-up purpose.  We aim to develop tools combining compact electronic devices for clinical measurements, Computational Fluid Dynamics modeling tools and Artificial Intelligence.


{%
  include link.html
  link="tools"
  text="Read mode"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/technology.png"
  link="resources"
  title=" New medical technologies to assess brain fluid dynamics in-vivo"
  flip=true
  text=text
%}

{% capture text %}
 Thanks to the collaboration of neurosurgeons, neurologists, radiologists and physicists we showed that brain mechanical response to intracranial vessel pulsation is associated with health deficit accumulation in a cohort of older adults with various neuropathologies. In order to understand the biological processes involved, we are now performing deep proteomics analysis from clinical data using data science technologies - eg. unsupervised clustering, neural network modelling.

{%
  include link.html
  link="team"
  text="Read mode"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/colormap.png"
  link="team"
  title="Biological processes involved in brain fluid dynamics."
  text=text
%}


