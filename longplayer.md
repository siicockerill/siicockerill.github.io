---
layout: default
---

# LongPlayer #

The browser can't cope with 1000 years worth of divs.
A years worth is going to be plenty for a UI.

Make a table for a year.
31 wide?
12 high.

{% months = ['J', 'F', 'M', 'A', 'M', 'J', 'J', 'A', 'S', 'O', 'N', 'D'] %}

<table>
{% for m in months %}
	<tr>
		<th>{{ m }}</th>
	</tr>
{% endfor %}
</table>