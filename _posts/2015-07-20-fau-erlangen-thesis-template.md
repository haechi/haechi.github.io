---
layout: post
title: "LaTeX Thesis Template"
date: 2015-07-19 22:00:00
categories: TeX
---

The XeTeX master file for my dissertation at the University of Erlangen is now on [Github](https://github.com/haechi/koma-thesis-erlangen). I wrote my thesis using [XeTeX](https://en.wikipedia.org/wiki/XeTeX) same as I did for for all of my academic reports. Over the years my personal requirements concerning typesetting and layout increased, so for my thesis it took me considerable efforts to set up the style and format.

My starting point was the [KOMA] (https://www.ctan.org/pkg/koma-script?lang=en) reporting class [scrreprt](https://www.ctan.org/pkg/scrreprt?lang=en), which offers good customization features. Since the thesis must be printed in the end, I choose a two page layout with right side chapter opening.

As required by the faculty the thesis had to include German and English content, so I settled with [XeTeX](https://en.wikipedia.org/wiki/XeTeX) as typesetting engine, due to the good unicode support. By doing so I could enter German special characters directly without any special escape character. XeTeX also allowed to use different standard font, after several iterations I went with

* [Open Sans](https://en.wikipedia.org/wiki/Open_Sans) as font for headings and the title page
* [Palatino](https://en.wikipedia.org/wiki/Palatino) main serif font, with matching math environment font
* [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) for source code listings

All fonts must be installed on the system, which is straight forward on OS X systems. One of the other feature of the KOMA class I used was to move the chapter numbers into the left margin of the page. The result can been seen below

![Chapter opening]({{ site.url }}/assets/images/koma-thesis-erlangen-03.jpg)

An example of the main serif font and the matching math environment is shown below

![Math environment]({{ site.url }}/assets/images/koma-thesis-erlangen-04.jpg)

The title page was formatted by hand since it had to match the requirement of the University of Erlangen. The title had to be written in German and in English together with some formalities.

 ![Title page]({{ site.url }}/assets/images/koma-thesis-erlangen-05.jpg)

Feel free to use the template for your own thesis. I hope it will help you short cut some time usually required for setting up complex LaTeX documents. You may download the template through the git repository  [https://github.com/haechi/koma-thesis-erlangen](https://github.com/haechi/koma-thesis-erlangen).
