---
layout: post
title:  "LaTeX Thesis Template"
date:   2015-07-19 22:00:00
categories: TeX
---

The LaTeX master file for my dissertation at the University of Erlangen is now on [Github](https://github.com/haechi/koma-thesis-erlangen). I wrote my thesis using [LaTeX](https://en.wikipedia.org/wiki/LaTeX) same as I did for for all of my academic reports. Over the year my personal requirements increase, so for my thesis it took considerable efforts to set up the style and format for the thesis. 

My starting point was the [KOMA] (https://www.ctan.org/pkg/koma-script?lang=en) reporting class [scrreprt](https://www.ctan.org/pkg/scrreprt?lang=en), which offers good customisation features. Since the thesis must be printed I choose a two page layout with right side chapter opening. 

Since the thesis had to include german and english I choose [XeTeX](https://en.wikipedia.org/wiki/XeTeX) as typesetting engine, for the unicode support. So I could enter German directly without any special escape character. XeTeX also allowed to use different standard font, after several iterations I settled on

* [Open Sans](https://en.wikipedia.org/wiki/Open_Sans) as font for headings and the title page
* [Palatino](https://en.wikipedia.org/wiki/Palatino) main serif font, with matching math environment font
* [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) for source code listings

All fonts must be installed on your system, which is straight forward on OS X systems. One of the other feature I used was to move the chapter numbers into the left margin. The result can been seen below

![Chapter opening]({{ site.url }}/assets/images/koma-thesis-erlangen-03.jpg)

An example of the  main serif font and the matching math environment is shown below

![Math environment]({{ site.url }}/assets/images/koma-thesis-erlangen-04.jpg)

The title page had to formatted by hand since it had to match the requirement of the Technical Faculty of the University of Erlangen. The title had to be written in German and in English together with some formalities. 

 ![Title page]({{ site.url }}/assets/images/koma-thesis-erlangen-05.jpg)

Feel free to use the template for your own thesis. I hope it will help you short cut some time usually required for setting up complex LaTeX documents.  A git repository is available under  [https://github.com/haechi/koma-thesis-erlangen](https://github.com/haechi/koma-thesis-erlangen).

