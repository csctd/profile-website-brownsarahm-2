# carosel

_a carosel version_

<div id='slideshow'>

<!--
the include works like copy-paste when the site is built
you can further customize the buttons in the html file, but this way they can be used in multiple places and this file stays light. 
 -->
```{include} _static/buttons.html
```



````{card-carousel} 2


```{card} 
:class-card: slide


![steps to make an issue](_static/img/issue.png)
+++ 

and a footer only on the site, not in full screen that is light
```


```{card} 
:class-card: slide

![pydata theme variables](_static/img/pydata.png)

+++
more footers
```


```{card} 
:class-card: slide, blue

![annotated repo](_static/img/repo.png)
```

```{card} 
:class-card: slide, pink

![steps to make an issue](_static/img/issue.png)
```

```{card} 
:class-card: slide, pink

^^^
![pydata theme variables](_static/img/pydata.png)

+++

footer can describe things for others
```


```{card} 
:class-card: slide, pink


![annotated repo](_static/img/repo.png)
+++
a footer here

```



````

</div>
