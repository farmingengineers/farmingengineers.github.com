---
layout: post
title: About the Farming Engineers
permalink: /about/
---

## What's with the name?

We’re Matt and Lisa, two engineering school graduates who started farming in 2008.  Lisa runs the farm and Matt writes software.  We rent our extra farmland to Farmer J.  We have over three acres of vegetables.  We used to have a few beef cows and a lot of chickens.  We’ve been assisted by various employees over the years. These days you’ll meet Devin, our full time helper, at some of our markets.  Our farm is USDA Certified Organic, and was the first certified organic farm in Clinton County, Indiana.

You can find us at the following farmers markets:

{% for market in site.data.markets %}
[{{market.name}}]({{market.link}}), {{market.season}}. {{market.description}}
{% endfor %}

You can find us on [facebook](https://www.facebook.com/pages/The-Farming-Engineers/136276076392635).
