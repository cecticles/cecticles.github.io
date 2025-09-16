# My Book Journal

Welcome! Here are the books I’ve read:

<ul>
  {% for book in site.books %}
    <li>
      <a href="{{ book.url }}">{{ book.title }}</a> — {{ book.author }}
    </li>
  {% endfor %}
</ul>
