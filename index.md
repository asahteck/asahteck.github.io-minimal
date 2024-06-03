## About this website

[About Me](./about-me.html)

[About My Advisor](./about-advisor.html)

[DREU 2024 Project](./DREU-project.html)

Weekly Update Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.permalink }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
