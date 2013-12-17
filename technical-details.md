---
layout: page
permalink: /technical-details/index.html
title: Technical Details
tags: [Technical, Details]
modified: 2013-11-02
image:
  feature: KY-Nailing-Machine.jpg
  credit: http://www.weakforcepress.com/
  creditlink: http://www.weakforcepress.com/
---

This page is intended for the tech aficionados and contains specific technical details about the inner workings of this site. I hope to shed some light on some of the special features that this website contains and maybe even help those interested ones implementing similar features in their website. Without further adieu, lets just dive in:

1. This website is built and updated with **Jekyll**[^1]. Jekyll is an awesome blog aware static site generator, and its highly useful for us academics. I will tell you why I used the word **Academics**. Back in 2008, when I was a freshman in college, I was provided with a hosting account with a domain name from the University registrar, and I badly wanted to host a blog. You know for swagger. I soon found out that the hosting servers for the students do not allow dynamic codes to run. My initial reaction was *NO PHP = NO BLOGGING*. Soon I stumbled across some beautiful blogs run on the same servers and some of those would be updated regularly. I came to know about the static site generators and fell in love. With a little bit of research I settled for Jekyll and my blogging experience changed forever.
1. `Kramdown`[^2] is the best of the bunch. As this is a Jekyll based website, the contents are written in Markdown. While I used `Rdiscount` as my markdown language for a while and absolutely loved it, I soon had to settle for something else as my blogging requirements grew. While `Rdiscount` is a lovely piece of software, it has a terrible relation with `MathJax-LaTeX`[^3] and messes up the TeX code when both are put together. As an Electrical Engineering and Mathematics major back then, I had to find an alternative and soon discovered `Kramdown`. Its a little different than traditional markdown languages and has a slightly different syntax, but as all other Markdown languages, it too has a steep learning curve and its no hassle to master it within an hour. I have been using it ever since.
1. As for aesthetics, this website features a modified version of the **["So Simple Theme"](http://jekyllthemes.org/themes/so-simple/)** by *Michael Rose* from [http://jekyllthemes.org/](http://jekyllthemes.org/). I like this theme because its minimalistic which greatly enhances the reading experience of the viewers. This theme also sports a responsive layout with a drop-down mobile menu which is awesome for reading on mobile devices on the go.
1. One of the major aesthetic changes I brought in the theme is to include a paginator in the home/latest posts page. This makes the website more readable and user-friendly. The navigation menu for the paginator uses an intelligent piece of code.
1. I have also included different category pages for my personal and mathematics related posts. I suppose these two will be the most frequented categories of this website. I will even include more in the future as I see fit.
1. I have been enjoying Medium.com as of lately and I simply love their **Estimated Reading Time (ERT)** of an article feature. What it does, it takes the word count of an article and calculates the **ERT** based on the average reading speed **(ARS)**. While **ARS** is simply an estimation and it differs from person-to-person, Medium uses 180 **Words-Per-Minute (WPM)** as their **ARS**. I figured out that **ARS** in this website's readers will fall between 210-330 **WPM**. You can find the **ERT** of any article in this blog in the blog meta information panel in the Left-Hand side of the article.
1. This website also utilizes the **"Pluralize"** plugin to generate singular/plural word based on the context explained in point 6. If the reading time is 1 minute, it delivers the singular word "minute", if else, the plural version "minutes" is delivered.
1. Providing the date in a naked form when the article has been created does not create a personal experience. To solve this the **"Timeago"** plugin has been implemented. It changes the article date and outputs it as a nice personal *"- days ago"* format.

[^1]: [Jekyll](http://jekyllrb.com/) transforms plain text into static websites and blogs.
[^2]: [kramdown](https://github.com/gettalong/kramdown) is yet-another-markdown-parser but fast, pure Ruby, using a strict syntax definition and supporting several common extensions.
[^3]: [http://www.mathjax.org/community/mathjax-in-use/mathjax-in-use-instructions-and-how-tos/](http://www.mathjax.org/community/mathjax-in-use/mathjax-in-use-instructions-and-how-tos/)
<a markdown="0" href="{{ site.url }}" class="btn">Check out my blog</a>