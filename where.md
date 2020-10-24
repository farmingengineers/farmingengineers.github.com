---
layout: post
title:  Where to find us
image: /assets/images/market-sept-2020.jpg
image2: /assets/images/market-sept-2020-mobile.jpg
permalink: /where/
---

We sell produce at several farmers markets in the Indianapolis area.

{% for market in site.data.markets %}
[{{market.name}}]({{market.link}}), {{market.season}}. {{market.description}}
{% endfor %}
