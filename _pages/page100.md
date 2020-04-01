---
permalink: /page100/
title: "Page 100 test page"

# OK
# layout: home

# header and footer, but no margins
# layout: default

# layout: andy
author_profile: false

toc: true
toc_label: "Contents"
toc_icon: "heart"  # corresponding Font Awesome icon name (without fa prefix)

sidebar:
  nav: "docs"
---

```
page.author_profile: '{{ page.author_profile }}'
layout.author_profile: '{{ layout.author_profile }}'
```

[Section 1](#section-1)

Tempor velit sint sunt ipsum tempor enim ad qui ullamco. Est dolore anim ad velit duis dolore minim sunt aliquip amet commodo labore. Ut eu pariatur aute ea aute excepteur laborum. Esse ea esse excepteur minim mollit qui cillum excepteur ex dolore magna. Labore deserunt fugiat incididunt incididunt sint ea. Consequat dolore aute laboris quis proident quis non et est consectetur ex eiusmod sit culpa.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

```python
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
x = 100
class A: pass
```

## section-1

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

### subby1

hi there

<i class="fa fa-info-circle"></i> <b>Note:</b><br><br>
Hey! This is how you make a notice - you add this to the end?
This is how you make a notice - you add this to the end?
This is how you make a notice - you add this to the end?
This is how you make a notice - you add this to the end?
`x=100` yeah you can't do python code blocks etc.
<br><br>
ok that was interesting!
{: .notice}

some html below to generate an alert - surely there is a simpler way?
<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Note:</b>
This is some info
Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.
<br>
<br>
</div>

<a href="#section-2" class="btn btn--success">Go to section-2</a>

> A sample blockquote.
> Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.
>
> >Nested blockquotes are
> >also possible.
> >Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.
>
> ## Headers work too
> This is the outer quote again.

what about this?

> A nice blockquote
{: title="Blockquote title"}

<div class="bs-callout bs-callout-danger">
  <h4>WARNING</h4>
  <p><b>Early-adopters</b>: the following steps will <b>NOT</b> work with the currently released Rhinoceros (5.x.x).  You will need to use WIP version of Rhinoceros.</p>
</div>

~~~~~~
This is also a code block.
~~~
Ending lines must have *at least* as
many tildes as the starting line. (in this case more...)
~~~~~~~~~~~~

term
: definition
: another definition

another term
and another term
: and a definition for the term

* * *

Hi again
Hi again
Hi again
Hi again

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3 though I wonder how big this can get?  |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

a simple table
a simple table
a simple table
a simple table
a simple table
a simple table
a simple table

| A simple | Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip. |
| with multiple | Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip. |


|               | **GitHub README.md**           | **GitHub Pages via /docs** |  Comment |
| sanitised raw | perfect                        | perfect  | The sanitised raw technique works perfectly in all scenarios, but it does mean precending all your image url references with `https://raw.githubusercontent.com/tcab/pagestest/master/` |
| naive         | ok but ugly github framed page | perfect  | Thus if its just GitHub Pages hosting, the naive technique is fine - even though the url has an extra part to it its still a short, easy url, with no `raw.githubusercontent.com` urls.  Naive technique not suitable on Github main page e,g, README.md due to the ugly github framed page issue - unless you are not expecting people to click on your images. |
| regeneration  | ok but flaky                   | flaky    | Flakiness is not good, even though this technique has the benefit of dynamically regenerating SVG files from PlantUML markdown source |



{::comment}
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
This is a comment which is
completely ignored.
{:/comment}

This is a text with a
footnote[^1].

[^1]: And here is the definition.

And this is abbreviation info. This is an HTML
example.  Its a rollover, not a clickable link!!

*[HTML]: Hyper Text Markup Language

This is *red*{: style="color: red"}.

<div markdown="span" class="alert alert-info" role="alert"><i class="fa fa-info-circle"></i> <b>Note:</b> yeah dunno if I can get this to work...</div>

### subby2

hi there again

## section-2

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.

Cupidatat ea do et in excepteur in. Ad nostrud ut est esse eu duis ea sunt eiusmod. Aliquip tempor veniam sint elit fugiat. Velit incididunt laboris amet incididunt labore dolore irure velit excepteur commodo deserunt laborum. Consectetur eu fugiat veniam veniam Lorem labore magna eiusmod. Ea occaecat reprehenderit pariatur consectetur minim labore ut aliquip.


## Attempt at including pure html

wow, it works.

<iframe src="http://html-patterns.atug.com/andybulkapatternautomation.html" name="frame1" scrolling="yes" frameborder="yes" align="center" height = "842px" width = "800">
</iframe>

## Part 2 - Design Pattern Tools as of 2006 (slides)

Here are the slides from a talk entitled "Design Pattern support in UML tools - part II" which I gave in October 2006 to the Melbourne Patterns Group, Australia.

<iframe src="http://html-patterns.atug.com/representingpatternsinumlandybulkaoct2006.html" name="frame1" scrolling="yes" frameborder="yes" align="center" height = "842px" width = "800">
</iframe>

## Video

Addendum
--------

As part of my Design Pattern Automation - Part 2 talk, I recorded some of that session.  Here is a youtube [video](http://www.youtube.com/watch?v=IjKClDX2dUU) of how to apply design patterns using IBM's [Rational](http://www-01.ibm.com/software/rational/uml/products.html) tool.  Apologies about the sound quality - just look at the pictures!

<iframe width="560" height="315" src="https://www.youtube.com/embed/IjKClDX2dUU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

