---
layout: single #collection
title: Design Patterns
permalink: /design-patterns/
excerpt: "Awesome list of Design Patterns"
header:
  #overlay_image: /assets/projects/autonomous-rc-car/hpi-racing-bmw-m3.png
  #overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  #caption: "Source: [**hpiracing**](http://www.hpiracing.com/de/kit/114343)"
  #show_overlay_excerpt: true
sidebar:
  nav: "design-patterns"
author_profile: false
---

## Introduction

The following list shows some important design patterns, which are design principles to achieve great program architectures.


- [Strategy](/design-patterns/strategy)
- [Observer](/design-patterns/observer)
- [Decorator](/design-patterns/decorator)
- [Factory](/design-patterns/factory)


## Design Principles

<p>
<b>Encapsulate what varies</b> <br>
Identify the aspects of your application that vary and separate them from
what stays the same.
</p>
{: .notice}

<p>
<b>Program to an interface, not an implementation. </b>
</p>
{: .notice}

<p>
<b>Favor composition over inheritance. </b>
</p>
{: .notice}

With composition it is possible to delegate behaviors instead of inheriting it.

<p>
Strive for loosely coupled designs between objects that interact.
</p>
{: .notice}

Loosely coupled designs allow us to build flexible object oriented
systems that can handle change because they minimize
the interdependency between objects. This principle can be seen in the [observer pattern](/design-patterns/observer).


<p>
<b>Open Closed Principle</b> <br>
Classes should be open for extension, but closed for modification.
</p>
{: .notice}

Patterns that extend a class without modifying the class itself are the
[observer](/design-patterns/observer) and the [decorator](/design-patterns/decorator) patterns.


<p>
<b>Dependency Inversion Principle</b> <br>
Depend upon abstractions. Do not depend upon concrete classes.
</p>
{: .notice}

## References

{% raw %}
<a href="https://www.amazon.de/Head-First-Design-Patterns-Freeman/dp/0596007124/ref=as_li_ss_il?ie=UTF8&linkCode=li2&tag=fjp-21&linkId=38bf781d92136c82d722d01735b6f3df&language=de_DE" target="_blank">
<img border="0" src="//ws-eu.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=0596007124&Format=_SL160_&ID=AsinImage&MarketPlace=DE&ServiceVersion=20070822&WS=1&tag=fjp-21&language=de_DE" >
</a>
<img src="https://ir-de.amazon-adsystem.com/e/ir?t=fjp-21&language=de_DE&l=li2&o=3&a=0596007124" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
{% endraw %}