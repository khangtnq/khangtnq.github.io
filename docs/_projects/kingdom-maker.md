---
layout: page
name: Kingdom Maker
studio: Global Worldwide
position: Client Developer
img_src: KingdomMaker.jpg
description: A RTS game that focus on kingdom building, get marries and raise new nobles, train armies and command them to fight in combats. 
app_link: https://play.google.com/store/apps/details?id=com.gww.km
skill: C#, Unity
---
<div>
<iframe style="display: block;margin: auto; border: none" width="560" height="315" src="https://www.youtube.com/embed/soZEDN2-jfk?si=5HAtmzqHzCXkTK6D" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><br/>

A RTS game that focus on kingdom building, getting married, raising new nobles, training armies and command them to fight in combats.
</div>

What I do: As a client developer, I implement features according to requirements and resolve issues related to the game.<br/><br/>
Studio: {{ page.studio }} <br/>
Skill: {{ page.skill }}

<h2>My main contributions:</h2>
- I replaced the whole legacy Unity Texts of the game with more modern TMP texts to support the game for future WebGL builds, because Unity Text is blurry in that build.
- I fixed localisation issues where texts are misplaced in other languages to ensure a consistent display of texts in all languages.
- I reduced the wait time to attack an army from up to 5s to instant. I did this by showing everything that is available first, then showing info that is fetched from the server later.
- I implemented the alternative cost system of the game, where you can buy something with another material.
- I also partook in fixing many other systems: battle pass reward display logic, optimised the building placement UI and road generations, combat texts and indicator display, a lot of null refs...
- Finally, I reported and fixed many small details of the games that are troublesome to me and others as players while playing the game, like overflown texts, misplaced chat boxes, overlapped UI...