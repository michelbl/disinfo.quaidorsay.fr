---
permalink: /en/our-tools
title: Our tools
navbar_items:
  - <a href="/en" class="header_mainnav_link">Home</a>
  - <a href="!SITE_URL!/en#our-actions" class="header_mainnav_link">Our actions</a>
  - <a href="/en/our-tools" class="header_mainnav_link">Our tools</a>
---

# Our tools

{% include breadcrumb.html %}

{% include our-tools/tool.html
icon="tool"
title="CGUs"
subtitle="Follow the changes to the Terms of Service"
desc="Services have terms that can change over time. CGUs enables users rights advocates, regulatory bodies and any interested citizen to follow the changes to these terms."
button-label="Discover"
button-href="/en/cgus" %}

{% include our-tools/tool.html
icon="tool"
title="DisEncyclopedia"
subtitle="Improve your practices and toolset"
desc="An open and collaborative resource that documents best practices, tools and actors, allowing all of those who counter information manipulation to improve the competence of the entire ecosystem."
button-label="Explore"
button-href="/encyclopedia" %}

{% include our-tools/tool.html
icon="tool"
title="Illegal Ads"
subtitle="Assess the legality of political ads"
desc="A crowdsourcing interface that allows citizens to view paid issue-based ads on Facebook and surface actors that do not respect the law. Currently only available for France, our code is open-source and we would be happy to collaborate with you to expand to other countries."
sublink-label="Send us an email!"
sublink-href="mailto:matti.schneider@diplomatie.gouv.fr?subject=AdsLegality"
button-label="Start classifying"
button-href="/political-ads" %}

{% include our-tools/tool.html
icon="tool"
title="Collaboration chat"
subtitle="Collaboratively detect, qualify and react to disinformation campaigns"
desc="A real-time chat that gathers actors, supports all the best practices identified in our encyclopedia, and offers the best tools as chatbots. If you are reading this, then we would probably like to have you on board."
sublink-label="Send us an email!"
sublink-href="mailto:matti.schneider@diplomatie.gouv.fr?subject=CollaborationChat"
button-label="Join"
button-href="/collaborate" %}

{% include our-tools/tool.html
icon="tool"
title="Bot Detection"
subtitle="Identify clusters of bots on Twitter"
desc="<p>A crawler that navigates Twitter follower relationships to identify clusters of suspicious accounts from a given seed account. It uses the free Twitter API and can thus be easily deployed.</p><p>Based on a manual annotation of over 400&nbsp;accounts, we have also used that dataset to <a href= \"/encyclopedia/qualification/tools#reliability-assessment\">assess the reliability</a> of usual bot detection tools such as Botometer.</p>"
button-label="Read the methodology"
button-href="/twitter-bot-clusters" %}