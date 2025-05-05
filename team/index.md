---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our lab is made up of a collaborative and diverse team of scientists. We value and actively work to create a lab, university, and community that is more diverse, inclusive, and equitable.

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'pi' and group == 'current'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'researcher' and group == 'current'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'postdoc' and group == 'current'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'grad' and group == 'current'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'undergrad' and group == 'current'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot, group: current"
%}
{:.center}

{% include section.html %}





![2023 team photo](/images/2023_lab_retreat_team.jpg "2023 team photo")

{% include section.html %}



# Alumni

Alumni from the lab have received prestigious awards (e.g., Knauss Marine Policy Fellowship, Fulbright Award), furthered their education in other graduate programs, and acquired jobs in government and non-profits. 


{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'pi' and group == 'alumni'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'researcher' and group == 'alumni'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'postdoc' and group == 'alumni'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'grad' and group == 'alumni'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'undergrad' and group == 'alumni'"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot, group: alumni"
%}
{:.center}



{% include section.html %}


## Funding

Our work is made possible by funding from several organizations.
{:.center}

{% capture content %}
  [![](/images/NSF_Logo.png)](https://www.nsf.gov/)

  [![](/images/Gund_logo.png)](https://www.uvm.edu/gund)

  [![](/images/fulbright-logo.png)](https://cies.org/)

  [![](/images/cdf_logo.png)](https://darwinfoundation.org/en//)

  [![](/images/unh_logo.png)](https://www.unh.edu/)

  [![](/images/nhsg-logo-blue.png)](https://seagrant.unh.edu/)
  
  [![](/images/prep_horiz.png)](https://prepestuaries.org/who-we-are/about-prep/)

  [![](/images/nhaes_logo.png)](https://colsa.unh.edu/new-hampshire-agricultural-experiment-station)

  [![](/images/logos/USDA_logo.png)](https://www.usda.gov/)
{% endcapture %}

{% include grid.html content=content %}





