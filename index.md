---
---

# Systems Aging Lab @ Westlake University

Biological systems such as tissues and cells, despite being made from noisy and error-prone components, are strikingly robustness due to intricate networks of control circuits collectively known as homeostasis. Homeostasis is fundamentally a systems-level, emergent phenomenon, difficult to understand from merely bottom-up description of individual parts. 

Our research aims to discovery "design" principles of homeostasis through its unraveling in aging and stress. Our methodology focuses on iterative theory-experiment cycles, traditionally found in physics. We use quantitative experiments to derive empirical "laws", build minimal, coarse‐grained models, which in turn motivate us to do new experiments to test them. In the recent decade, detailed and painstaking quantiative measurements in various organisms have yielded such empirical "laws". These are specific yet generalisable, simple yet predictable mathematical equations describing the dynamics of aging. We are delineating the principles behind these quantitative "laws" and validate them in experiments and data.

At the time, we aim to resolve mechanistic mysteries in cell physiology and tissue homestasis surrounding important genetic pathways discovered in aging research. Our top-down mathematical modeling and quantiative experiments can precisely define the functions of genes and genetic pathways on the systems-level, which are difficult to derive from molecular details alone. Biological questions that motivate us include: How can the same genome gives rise to cell types that vary so much in lifespan? How can mammals of the same size differ in lifespan by an order of magnitude? Whether and how do organisms control their rates of aging? 


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
