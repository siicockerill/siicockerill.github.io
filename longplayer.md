---
layout: default
---

# LongPlayer #

The browser can't cope with 1000 years worth of divs.
A years worth is going to be plenty for a UI.

Make a table for a year.
31 wide?
12 high.

<table>
{% for m in (1..12) %}
	<tr>
		<th>{{ m }}</th>
		{% for d in (1..31) %}
		<td>{{ d }}</td>
		{% endfor %}
	</tr>
{% endfor %}
</table>