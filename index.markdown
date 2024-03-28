---

layout: post
title:  "woozoo"

---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

---

Welcome to My Home Page

![main image](/assets/img/main/main.png)

산책하자



쉼은



눈을 감고



목을 기대는 것



그 두 개만 하면 된다.