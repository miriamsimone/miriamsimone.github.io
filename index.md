---
layout: default
---

<div class="home">
    <p>A serial exploration of the resonances between mathematical structures, embodied experience, and queer being. This is my <em>Gödel, Escher, Bach</em>.</p>
    
    <h2 style="margin-top: 3rem; margin-bottom: 1.5rem;">Essays</h2>
    
    <ul class="post-list">
    {% for post in site.posts %}
        <li>
            <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
            <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
            {% if post.excerpt %}
                <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
            {% endif %}
        </li>
    {% endfor %}
    </ul>
</div>
