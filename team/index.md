---
title: Team
---

# <i class="fas fa-users"></i>Team

<!-- section break -->

{% capture html %}
{% include team-list.html role="faculty" %}
{% include team-list.html role="phd" %}
{% include team-list.html role="grad" %}
{% include team-list.html role="undergrad" %}

{% endcapture %} 

{% include centerer.html html=html %}

<!-- section break -->


<!-- section break -->

## Funding
Moving forward to achieve our goals we have been awarded $599,998.00 by the National Science Foundation on  Development of a Secure and Privacy-Preserving Workflow Architecture for Dynamic Data Sharing in Scientific Infrastructures.
{:.center}

{%
  include gallery.html
  flat="true"
  fit="false"

  image1="images/download.jpg"
  link1="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1839746"
  tooltip1="NSF"

  
%}
