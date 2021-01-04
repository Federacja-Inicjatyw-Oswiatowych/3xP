---
layout: default
---

3xP
===
Opis projektu, instrukcje.

Fiszki
---

<ul>
    {% for card in site.flashcards %}
    <li>
        <h2><a href="{{ card.url }}">{{ card.title }}</a></h2>
    </li>
    {% endfor %}
</ul>