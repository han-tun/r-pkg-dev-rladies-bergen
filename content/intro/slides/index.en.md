---
outputs:
- Reveal
title: Become an R Package Developer!
hidden: true
layout: list
weight: 11
output: hugodown::md_document
countdown: true
rmd_hash: ac90e67a32440a98

---

Become an R Package Developer!
==============================

:wave: Hei!

------------------------------------------------------------------------

I've never been in Bergen
-------------------------

:sob:

But... I've been to Norway two times when I was an intern in Gothenburg, Sweden!

------------------------------------------------------------------------

{{< figure src="palace.JPG" alt="Maëlle in front of royal palace in Oslo" caption="Me in front of royal Palace in Oslo, 2010" width=500 >}}

------------------------------------------------------------------------

{{< figure src="evenstad.JPG" alt="Maëlle standing and laughing on a dirt road" caption="Me in (near?) Evenstad, 2010. Picture by Anne-Sophie Bonnet-Lebrun" width=500 >}}

------------------------------------------------------------------------

My R package development creds
------------------------------

I really :heart: R package development

-   Volunteer editor for [rOpenSci Software Peer Review](https://ropensci.org/software-review)

-   At work, maintenance of [rOpenSci dev guide](https://devguide.ropensci.org)

-   Created the [R-hub blog](https://blog.r-hub.io) (:wave: [guest author Julia](https://blog.r-hub.io/2020/01/08/cran-error/)!)

-   Working on the [HTTP testing in R](https://books.ropensci.org/http-testing/) book

------------------------------------------------------------------------

Why develop an R package?
-------------------------

Easiest way to share code/data/R Markdown templates... with

-   (future) you,

-   the collaborators you know,

-   and the collaborators you don't.

------------------------------------------------------------------------

Why learning about package development?
---------------------------------------

[Jon Calder](https://joncalder.co.za/)'s very good [wording](https://github.com/iandurbach/datasci-fi/tree/master/docs/packages/slides)

-   To share code (and data)

-   To leverage existing tooling

-   To contribute to other packages

------------------------------------------------------------------------

Who can write a package? YOU!
-----------------------------

Susan Johnston's [wise words](https://github.com/susjoh/fibonacci).

-   Can you open R or RStudio?

-   Can you install a package?

-   Have you ever written a function in R?

-   Could you *learn* how to write a function in R?

-   **You can write a package in R**

------------------------------------------------------------------------

What is a package?
------------------

> Pour réduire ses craintes, il faut se dire que ce n'est ni plus ni moins qu'un dossier organisé d'une manière contrainte.

> To be less afraid you have to tell yourself that it's simply a folder organized in a constrained way.

[Sébastien Rochette](https://thinkr.fr/transformer-plusieurs-scripts-eparpilles-en-beau-package-r)

------------------------------------------------------------------------

Automation!
-----------

{{< figure src="automate_meme.jpg" alt="Small monster saying to automate all the things" caption="Meme image by [Allie Brosh](https://en.wikipedia.org/wiki/Hyperbole_and_a_Half)" >}}

------------------------------------------------------------------------

Automating... How?
------------------

Remember Clippy?

------------------------------------------------------------------------

Automating... How?
------------------

Get to know an actually useful Clippy, `{usethis}`!

{{< figure src="https://usethis.r-lib.org/reference/figures/logo.png" alt="usethis logo, a robot" >}}

------------------------------------------------------------------------

`usethis` and co
----------------

{{< tweet 935562495816753153 >}}

------------------------------------------------------------------------

Website tour
------------

:link: <a href="https://tiny.cc/r-pkg" class="uri">https://tiny.cc/r-pkg</a>

Slides, notes from the demo, further resources, comments!

------------------------------------------------------------------------

Time for a demo :rocket:
------------------------

Notes on the [course website](/intro/demo)

Also refer to the [Whole game chapter of the R packages book by Hadley Wickham and Jenny Bryan](https://r-pkgs.org/whole-game.html)

------------------------------------------------------------------------

Back from the demo
------------------

-   [`devtools::load_all()`](https://devtools.r-lib.org//reference/load_all.html) (and then install)

-   `{usethis}` for all the things.

------------------------------------------------------------------------

R CMD check (devtools::check())
-------------------------------

{{< figure src="sign.JPG" alt="Sign near a dirt road, indicating there might be farm animals" caption="Picture by Anne-Sophie Bonnet-Lebrun" width=500 >}}

------------------------------------------------------------------------

So what's really hard?
----------------------

-   Writing good code

-   Writing a good interface

-   Writing good docs

------------------------------------------------------------------------

More with packages
------------------

-   [`usethis::use_rmarkdown_template()`](https://usethis.r-lib.org/reference/use_rmarkdown_template.html)

-   distributing data [`usethis::use_data()`](https://usethis.r-lib.org/reference/use_data.html)

-   packaging a Shiny app (look for examples, and [golemverse](https://golemverse.org/))

-   Reproducible analyses, [research compendium](https://annakrystalli.me/rrresearch/10_compendium.html)

------------------------------------------------------------------------

Less with packages
------------------

-   If developing a package for wider distribution, check it does not exist yet.

-   Miles McBain's post ["Project as an R package: An okay idea"](https://milesmcbain.xyz/posts/an-okay-idea/)

------------------------------------------------------------------------

Questions?
----------

Write them in the Zoom chat, or as a comment in the course website, or as an issue in the course repository.

------------------------------------------------------------------------

Time for a break! :coffee:
--------------------------

<!--html_preserve-->

<div id="timer_hugo" class="countdown" style="top:100;left:0;" data-warnwhen="0">

<code class="countdown-time"><span class="countdown-digits minutes">05</span><span class="countdown-digits colon">:</span><span class="countdown-digits seconds">00</span></code>

</div>

<!--/html_preserve-->

