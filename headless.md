---
title: Content Management Systeme heute
---

# Content als eigenes Layer vs. Content als Teil einer Publikation

Ich möchte heute kurz einiges über neue Entwicklungen bei Content Management Systemen erzählen. Zwar verwenden die meisten Websites heute noch Systeme wie Wordpress und Typo 3, also das, was wir als CMS kennen. Aber seit etwa 10 Jahren hat sich die Welt der Content Management Systeme deutlich verändert. Das wichtigste Stichwort oder Buzzword heisst dabei *headless*. Gemeint ist damit, dass der Prozess der dynamischen Seiten-Generierung, wie wir ihn von den traditionellen Content Management Systemen kennen, nicht mehr bestimmt, wie ein Content Management System organisiert ist. Content Management Systeme sind für den Content zuständig, aber nicht mehr dafür, wie dieser Inhalt weiterverarbeitet und publiziert wird. 



Headless
 
Warum man von einem Headless CMS spricht, erklärt ganz kurz dieses Video: 

 Gute kurze Erklärung: [\(279\) Headless CMS explained in 2 minutes \- YouTube](https://www.youtube.com/watch?v=-Uor3I0n_vQ)


# Content Modelling

Durch die Headless CMS ist ein Aspekt des Content Managements in den Vordergrund gerückt, der bisher oft dadurch verdeckt war, dass die Inhalte in einem CMS Seiten zugeordnet waren. Wenn die Seite die grundlegende Einheit für die Inhalte ist, dann muss man sich nicht unbedingt um eine zusätzliche formale Struktur bemühen. Wenn aber der Inhalt von Seiten unabhängig ist, wie z.B. bei Single Page-Applikationen, dann muss die inhaltliche Struktur für sich definiert werden. 

[Structures of Content \- Storyblok](https://www.storyblok.com/docs/guide/essentials/content-structures)

https://craftcms.com/docs/getting-started-tutorial/configure/modeling.html#get-familiar-with-content-modeling-in-craft


# Wie wird der Inhalt publiziert?

Wenn der Inhalt so strukturiert vorliegt und zugänglich ist, dann kann völlig unterschiedlich publizieret werden, und man kann verschiedene Publikationsmöglichkeiten kombinieren und sie auch schnell wechseln oder weiterentwickeln. Inhalte sind Komponenten von Applikationen, die sehr unterschiedlich Funktionen haben können. 

Es kann sein, dass derselbe Inhalt für manche Clients serverseitig gerendert wird, und dass bei anderen der Client für das Rendering zuständig ist. Es kann auch beides miteinander verbunden sein, und es können in die Inhalte Komponenten aus anderen Quellen integriert sein. Genau dafür passt das Modell eines monolithischen System nicht. 


Static Site Generators

![](https://static.agilitycms.com/cms-vs-ssg-y.png) aus [What's the Difference between Headless CMS and Static Site Generator? \| Agility CMS](https://agilitycms.com/resources/posts/what-s-the-difference-between-headless-cms-and-static-site-generator)

Single Page Apps

# APIs

## REST APIs

## GraphQl APIs

—-

Es war nicht unsere Absicht das Adolf Loos-Haus zu beschädigen, das ein wertvolles öffentliches Gut ist. Wir bedauern, wenn es dazu gekommen ist. 

Lichtblick 

Content as code

Static site generator for. Static content
React for dynamic content, both possible by API access

Main reasons for choice: scalability and flexibility 

Keine on premises Systeme mehr 

https://www.contentful.com/events/2011-dxpertsinaction-dach/watch/


Headless CMS für News-Organisationen: [(279) Superdesk Essentials: Welcome to Superdesk, Your New Digital Newsroom - YouTube](https://www.youtube.com/watch?v=MQ09P2Fz4Io "(279) Superdesk Essentials: Welcome to Superdesk, Your New Digital Newsroom - YouTube")


