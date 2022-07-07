# ERIKSENS CONSULTING AS

## Velcome to my simple web page.

You are probably looking for a way to reach me:

[Roger Eriksen](mailto:roger@eriksens.io)
[+47 909 48 146](tel:4790948146)

## My blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
