---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: home
title: Building Websites in GitHub
---

## Description
{{ site.description }}
{% assign lead = site.team_members | where:"role", "project lead" | first %}
The project is led by {{ lead.name }}.
[See our full team](about#team)
More details about the project are available from the [About page](about).

Have any questions about what we do? [We'd love to hear from you!](mailto:{{ site.email }})

[Here is an example of a lesson]({{ page.lesson-example }}).

