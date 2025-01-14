---
layout: default
title: "16-761: Mobile Robots"
---

# Schedule

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Lecture</th>
      <th>Assignment Released</th>
      <th>Assignment Due</th>
    </tr>
  </thead>
  <tbody>
    {% for e in site.data.schedule %}
    <tr>
      <td>{{ e.date }}</td>
      <td>{{ e.lecture }}</td>
      <td>{{ e.assignment_released }} {% if e.assignmenturl %} <a href="{{ e.assignmenturl }}">here</a> {% endif %}</td>
      <td>{{ e.assignment_due}}</td>
    </tr>
    {% endfor %}
  </tbody>
</table>
