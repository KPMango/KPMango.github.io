classes: wide
<table>
  <thead>
    <tr>
      {% for column in site.data.test1[0] %}
        <th>{{ column[0] }}</th>
      {% endfor %}
    </tr>
  </thead>
  <tbody>
    {% for row in site.data.test1 %}
      <tr>
        {% for cell in row %}
          <td>{{ cell[1] }}</td>
        {% endfor %}
      </tr>
    {% endfor %}
  </tbody>
</table>
