---
---

The test works.

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}

Here we check if quoting works.

{% quote datta_upper-echelon_2014 %}
We find that 'strategic' CFOs with an elite MBA (generalist) consistently command a compensation premium, while 'accounting' CFOs (specialist) and CFOs with a non- MBA master's degree, even from an elite institution, do not.
{% endquote %}

Does it look OK?

Here is a small markdown change. No extra libs.

# Cited bibliography

{% bibliography --cited %}

# Entire bibliography

{% bibliography %}

