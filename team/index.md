---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# <i class="fas fa-users"></i> Team

Our lab is made up of a collaborative and diverse team of scientists. We value and actively work to create a lab, university, and community that is more diverse, inclusive, and equitable.

If you are interested in joining the lab, please [read through the process in our lab handbook](https://quantmarineecolab.github.io/lab-manual/04-recruitment.html). 

## Current Lab Members

{% include list.html data="members" component="portrait" filter="role == 'pi' and group != 'alumni'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi' and group != 'alumni'" %}

{:.center}

{% include section.html %}

![2023 team photo](/images/qmel_lab_2025.jpeg "2025 team photo")

{% include section.html %}

# Alumni

Alumni from the lab have received prestigious awards (e.g., Knauss Marine Policy Fellowship, Fulbright Award), furthered their education in other graduate programs, and acquired jobs in government and non-profits.


{% include list.html data="members" component="portrait" filter="group == 'alumni'" style="small" %}

{:.center}


## Funding

Our work is made possible by funding from several organizations.
{:.center}

{% include section.html %}

{% capture content %}

  [![](/images/NSF_Logo.png)](https://www.nsf.gov/){width=25%}
  [![](/images/Gund_logo.png)](https://www.uvm.edu/gund){width=25%}
  [![](/images/fulbright-logo.png)](https://cies.org/){width=25%}
  [![](/images/cdf_logo.png)](https://darwinfoundation.org/en//){width=25%}
  [![](/images/unh_logo.png)](https://www.unh.edu/){width=25%}
  [![](/images/nhsg-logo-blue.png)](https://seagrant.unh.edu/){width=25%}
  [![](/images/prep_horiz.png)](https://prepestuaries.org/who-we-are/about-prep/){width=25%}
  [![](/images/nhaes_logo.png)](https://colsa.unh.edu/new-hampshire-agricultural-experiment-station){width=25%}
  [![](/images/logos/USDA_logo.png)](https://www.usda.gov/){width=25%}
{% endcapture %}

{% include grid.html style="square" content=content %}
