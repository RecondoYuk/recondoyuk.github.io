  # Hello World! #
## About Me ##
I am a mess of a person just trying to learn a new skill or two.  I figure Elon is going to need someone to feed people on Mars so I'd better learn the tech side of things!
## Contact Information ##
Don't.
But you can check out this [link](https://recondoyuk.github.io/HelloWorld/ "Hello World")

---
## Blog ##
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
