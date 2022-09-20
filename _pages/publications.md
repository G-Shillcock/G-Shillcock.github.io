---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <u><a href="https://scholar.google.co.uk/citations?hl=en&view_op=list_works&gmla=AJsN-F4CgTlEsspngzYPKYrF1skHMnUYx0thMDQdRBo3QVWkO0s_4WnWUWTgNcTOIuMMVRLmO5rsxcTLGfRZIo760Cu67f2sUFGG7LGKGeh7aVOpDIvfZrk&user=hpWPCOkAAAAJ">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
