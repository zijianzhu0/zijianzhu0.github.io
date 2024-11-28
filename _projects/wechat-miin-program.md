---
layout: page
title: WeChat Mini Program (Jun2020)
description: 
img: assets/img/tb-mini-program.png
importance: 1
category: personal
---

[What is mini-program?](https://en.wikipedia.org/wiki/WeChat#WeChat_Mini_Program)

Why do I started this project?

WeChat is THE most popular app in China, billions of Chinese use it everyday. You also might have read it somewhere that WeChat is a mega app that has everything one needs in a single app.

So I wanted to know how it works. How does WeChat host other "mini-program" in it. So I started out from the official documentation and went from there.

It turns out that each min-program is a tiny piece of website, WeChat is providing the datacenter to host all the websites and gives the users a special browser to use mini-program. The special about the browser is integration. It is highly integrated with WeChat ecosystem:

- Payment system: people can use WeChat pay to purchase goods and services within the browser.
- Account authentication: since none wants to type anything to log in accounts, WeChat provide APIs to let developers to access the WeChat account information, so all users have to do is granting the access to the developer

I eventually built a mini-program that converts temperatures between Fahrenheit and Celsius

<div class="row justify-content-center">
    <div class="col-sm-9 col-md-6 col-lg-6 mt-3 mt-md-0">
    <!-- col-sm-12 col-md-8 col-lg-6: Limits the image width to 100% of the column on small screens, 8/12 (66.7%) of the row width on medium screens, and 6/12 (50%) on large screens. -->
        {% include figure.liquid loading="eager" path="assets/img/wechat-mini-program.gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption text-center">
    User interface
</div>