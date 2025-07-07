---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
description: I am a game developer with 4 years experience making games. I am skilled at Unity and C#.<br/>
  I enjoy making games and play video games, my favorite genres are co-op, RTS, anime, strategy, and base-builder.<br/>
---

<h1>Projects</h1>
<div>
    {% for worked_game in site.projects %}
        <hr> 
        <h2><a style="color: #159957" href="./{{ worked_game.url }}">{{ worked_game.name }}</a></h2>
        
        {% if worked_game.app_link %}
            <a href="{{worked_game.app_link}}"><img class="company-image" src="/assets/{{worked_game.img_src}}"></a><br/>
        {% else %}
            <a href="{{worked_game.url}}"><img class="company-image" src="/assets/{{worked_game.img_src}}"></a><br/>
        {% endif %}

        {% if worked_game.sub_studio %}
            <p>Subsidiary studio: {{ worked_game.sub_studio }}</p>
        {% endif %}
        <p>Studio: {{ worked_game.studio }}</p>
        <p>Position: {{ worked_game.position }}</p>
        <p>{{ worked_game.description | markdownify }}</p>
         
    {% endfor %}

   
</div>