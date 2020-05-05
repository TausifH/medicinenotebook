---
title: "Peripheral Vascular Disease"
permalink: "/peripheral-vascular-disease"
---

Hi! I am Sal, web designer & developer at WowThemes.net. The free items I create are my side projects and **Mundana for Jekyll** is one of them. You can find **all the work I release for free [here](https://www.wowthemes.net/category/free-themes-templates/)**. 

You have my permission to use the free items I develop in your personal, commercial or client projects. If you'd like to reward my work, I would be honored and I could dedicate more time maintaining the free projects. 

Thank you so much!

<a class="btn btn-danger" href="https://www.wowthemes.net/donate/">Buy me a coffee</a>

<div class="sticky-top sticky-top-offset">
    <ol class="list-featured">				
        {% for post in site.categories.peripheral-vascular-diseae %}                
            <li class="mb-4">
            <span>
                <h6 class="font-weight-bold">
                    <a href="{{site.baseurl}}{{ post.url }}" class="text-dark">{{ post.title }}</a>
                </h6>
                <span class="d-block text-muted">
                    In <span class="catlist">
                    {% for category in post.categories %}
                    <a class="text-capitalize text-muted smoothscroll" href="{{site.baseurl}}/categories.html#{{ category | downcase }}">{{ category }}</a><span class="sep">, </span>
                    {% endfor %}
                    </span>
                </span>
            </span>
            </li>                
        {% endfor %}   
    </ol>
</div> 