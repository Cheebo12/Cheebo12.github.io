---
layout: home
---
<!-- Non-programming section -->
{% if site.theme_config.show_nonprogramming_list == true %}
  <h2>{{ site.theme_config.home.title_nonprogramming_list }}</h2>
  {% include horizontal_list.html collection=site.data.home.nonprogramming_entries %}
{% endif %}
