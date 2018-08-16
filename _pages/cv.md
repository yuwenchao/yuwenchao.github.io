---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /
---

{% include base_path %}

Also available in <a href=''>PDF</a> format.

Education
======
* Ph.D. in Computer Science, University of California Los Angeles, 2019 (Expected)
* M.S. in Computer Science, Institute of Computing Technology, Chinese Academy of Sciences, 2014
* B.Eng. in Software Engineering, Wuhan University, 2011

Research and Project Experience
======
* Research Assistant, University of California Los Angeles, Sept. 2014
  * Modeling co-evolution across multiple networks. Work published in SDM
    * Proposed a shared temporal matrix factorization framework to model co-evolution across multiple networks.
    * Demonstrated the benefits of this approach on the tasks including cross-network link prediction and community detection.
  * Link prediction with spatial and temporal consistency in dynamic networks. Work published in IJCAI
    * Proposed a link prediction model with spatial and temporal consistency, to predict links in a sequence of networks over time.
    * The proposed model characterized the network dynamics as a function of time, which integrates the spatial topology of network at each timestamp and the temporal network evolution. Advertiser competition analysis in search advertising. Work published in ICDM
  * Modeled the advertiser competition network, and explored the relationship between competition network and search provider’s revenue
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Service
======
* Currently signed in to 43 different slack teams
