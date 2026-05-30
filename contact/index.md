---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are based in the [Department of Zoology](https://www.otago.ac.nz/zoology) at the [University of Otago](https://www.otago.ac.nz/), Dunedin, New Zealand. Feel free to get in touch!

{%
  include button.html
  type="email"
  text="caroline.beck@otago.ac.nz"
  link="caroline.beck@otago.ac.nz"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/zoology.JPG"
  caption="Department of Zoology"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/greentads.jpg"
  caption="Xenopus laevis tadpoles"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
**Mailing Address**  
Beck Lab, Department of Zoology  
University of Otago  
P.O. Box 56, Dunedin 9054  
New Zealand
{% endcapture %}

{% capture col2 %}
**Location**  
Zoology Building  
340 Castle Street  
Dunedin, New Zealand
{% endcapture %}

{% capture col3 %}
**Links**  
[Department of Zoology](https://www.otago.ac.nz/zoology)  
[University of Otago](https://www.otago.ac.nz/)
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
