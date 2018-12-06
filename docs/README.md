# Chapter 11 Animations - Exercise Yoko
A first acquaintance with Animations and transitions.

## Get the slides
Slides for this exercise can be found [here](https://chamilo.hogent.be/index.php?go=CourseViewer&application=Chamilo%5CApplication%5CWeblcms&course=28832&tool=Document&publication_category=197806&browser=Table&tool_action=Browser).

## Get the files
The starter files can be downloaded by clicking on the green **Clone or Download** button at the top of this page, or by clicking [this link](https://github.com/WEBAPPLICATIES1/11exAnimations/archive/master.zip).
> Remark: You can ignore the **docs** folder. The files you need are located in the **exercise** folder.

## Get a preview
An online preview of the deployed website can be found [here](https://webapplicaties1.github.io/11exAnimations/).
https://webapplicaties1.github.io/11exAnimations/

## Exercise
<!-- TODO: Translate in English. -->
Vul de SCSS file aan voor de volgende zaken te bekomen vanaf de website in **tablet modus** is.
- Bij het hoveren over de menu items in de nav bar, willen we een animatie zodat links even op en neer “bouncen”
    - Voeg de animation toe met een lengte van 400ms
    - Zorg voor de keyframe waar de links van boven naar onder verschuiven
        - Op 0% en 100% moeten de links op de originele plaat staan
        - 50% op -10px
        - 80% op 3px
- Wanneer we over de figures in de courses section hoveren willen we de figcaption laten binnenvliegen vanaf links
    - Geef de figcaption een begin position van -200px
    - Position: relative;
    - Left: -200px;
    - Zorge voor een transition van 300ms waar we de figcation 200px over de x-as verschuiven
- Bij het hoveren over de popular recipes willen we de links laten schalen tot 1.2. Zorg voor een transition van 300ms en zorg dat de tranform-origin aangepast wordt naar center left.

- Voeg nog een extra animatie toe als we de website op grote schermen bekijken. (min 992px)
    - Bij het inladen van de website willen we dat de banner geanimeerd op zijn plaats schuift
        - We willen een animation op de header picture die 2s duurt
        - Voorzie de gepaste keyframes zodat de positie van de banner begint op -200px en verschuift tot zn originele positie op 0px.

## Solution
A possible solution to this exercise can be found in [the solution branch of this repository](https://github.com/WEBAPPLICATIES1/11exAnimations/tree/solution/exercise).
