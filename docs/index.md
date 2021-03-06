---
---

# NoGA

<div class="imgrights">

<img src="/NoGA.jpg" alt="Photo titled Surveillance" style="width:100%;" />
<div class="bottom-right">
"Surveillance" by Jonathan McIntosh, CC BY-SA 2.0 (<a href="https://ccsearch.creativecommons.org/photos/c3f655bb-d0b5-4408-b755-f313c0e0259b">source</a>).
</div>

</div>

## Waarom zou je website data weggeven aan derden?

Veel organisaties - variërend van start-ups tot gemeentes, scholen en universiteiten - maken gebruik van Google Analytics. 
Een alternatief is de analyse van je website data zelf uit te voeren met open source Web Analytics software. 
Dit project onderzoekt de beperkingen van het gebruik van Google Analytics, 
maakt concreet hoe organisaties open source software kunnen gebruiken 
en brengt in kaart in hoeverre dit tot betere analyse data leidt 
(bijvoorbeeld omdat ad-blockers dan minder effect op de verzamelde data hebben). 
Uiteindelijk zullen organisaties zo inzien dat ze baas zouden moeten worden en blijven over de eigen website data.

_Blogs:_

{% for post in site.posts limit: 3 %}
+ {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
> {{ post.excerpt }}
{% endfor %}

_[More...](archive.html)_
