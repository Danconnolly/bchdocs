## Daniels Collection of Documents

A collection of documents on crypto-currency topics.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl + post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

