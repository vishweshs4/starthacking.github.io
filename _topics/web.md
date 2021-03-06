---
layout: page
title: Web
categories:
  - mac
  - windows
  - gnu-linux
hierarchy:
  -
    name: "Topics"
    path: "/topics"
---

In a nutshell, websites are made of HTML, CSS, and JavaScript.

### HTML and CSS

HTML stands for Hypertext Markup Language and will create the structure and
content of your web page. CSS stands for Cascading Style Sheets and describes
how your HTML elements look on screen. They often work together to create
your page and make it pretty. Here are a few tutorials to help you get
started with HTML and CSS!

- [Codecademy][codecademy]
- w3schools [HTML][w3html] and [CSS][w3css]
- Build a site with [GitHub Pages][first-site]

### Javascript

Javascript can be used to change the content of your website and add
different interactive features.

- [Javascript basics][javascript]
- [Javscript tutorial][js-tutorial] for all levels

## Getting Started With [x]

{% for topic in site.topics %}
    {% if topic.categories contains 'web' %}
- [{{ topic.title }}]({{ topic.url }})
    {% endif %}
{% endfor %}

[codecademy]: https://www.codecademy.com/catalog/language/html-css
[w3html]: https://www.w3schools.com/html/default.asp
[w3css]: https://www.w3schools.com/css/default.asp
[first-site]: https://pages.github.com/
[javascript]: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
[js-tutorial]:http://www.htmldog.com/guides/javascript/