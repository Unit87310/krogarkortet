---
layout: home
---

# Välj ett kort

<ul>
  {% for recipient in site.data.recipients %}
    <li>
      <a href="{{ site.baseurl }}/cards/{{ recipient.id }}.html">
        {{ recipient.firstName }} {{ recipient.lastName }}
      </a>
    </li>
  {% endfor %}
</ul>
