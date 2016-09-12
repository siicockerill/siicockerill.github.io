---
layout: default
---

# LongPlayer #

The browser can't cope with 1000 years worth of divs.
A years worth is going to be plenty for a UI.

Make a table for a year.
Each row is a new month (12 rows).
Columns for 5 weeks max.

<table>
{% for m in (1..12) %}
	<tr>
		<th>{{ m }}</th>
		{% for d in (1..35) %}
		<td>x</td>
		{% endfor %}
	</tr>
{% endfor %}
</table>