---
title: People
nav:
  order: 3
  tooltip: Collaborators
---

# <i class="fas fa-users"></i>Collaborations


{% include section.html %}

# Modelling
{%
  include list.html
  data="members"
  component="portrait"
  filters="field: modelling"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer"
%}
{:.center}

{% include section.html background="images/banner.png" dark=true%}



{% include section.html %}

## Join

### PhD students / Post Doctoral Researcher

If you are interested by our research, I can help you to submit fellowship applications.

Do not hesitate to contact me to discuss about opportunities.


{% include link.html type="external" link="./contact" text="Contact me" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
