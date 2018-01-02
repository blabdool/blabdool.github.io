---
layout: page
permalink: /about/index.html
title: Bilkisu Larai Muhammad-Bello
tags: [Bilkisu, Larai, Muhammad-Bello, Cloud Computing]
imagefeature:
chart: true
---
<figure>
  <img src="blabdool.github.io/images/about_me_image.jpg" alt="Bilkisu Larai Muhammad-Bello">
  <!-<figcaption> Bilkisu Larai Muhammad-Bello</figcaption> -->
</figure>

{% assign total_words = 0 %}
{% assign total_readtime = 0 %}
{% assign featuredcount = 0 %}
{% assign statuscount = 0 %}

{% for post in site.posts %}
    {% assign post_words = post.content | strip_html | number_of_words %}
    {% assign readtime = post_words | append: '.0' | divided_by:200 %}
    {% assign total_words = total_words | plus: post_words %}
    {% assign total_readtime = total_readtime | plus: readtime %}
    {% if post.featured %}
    {% assign featuredcount = featuredcount | plus: 1 %}
    {% endif %}
{% endfor %}


Hi! My name is **Bilkisu Larai Muhammad-Bello**, I like to shorten to Bilkisu. I am a grad student of [Computer Science and Electrical Engineering Department](http://www.eng.kumamoto-u.ac.jp/english/dept/dept06.html) at [Kumamoto University](http://www.kumamoto-u.ac.jp/) and, this is my personal blog. My research is about service selection in Cloud Computing and Workflow Scheduling in the Cloud environment. I am also interested in Machine Learning and data analytics, so I am taking the [Cousera course](https://www.coursera.org/learn/machine-learning). In the past three years I've been learning a lot of new things. I am currently learning web development, so this is like my test site. I can be reached by [email](blabdool@gmail.com) or [Facebook](http://facebook.com/bilkisua), [Twitter](http://twitter.com/blabdool), [LinkedIn](https://www.linkedin.com/in/bilkisu-bello-9b534474/), and [Quora](https://www.quora.com/profile/BILKISU-MUHAMMAD-BELLO), so give a shoutout.

**Things I have done recently**
* I published a paper called [A transparent approach to performance analysis and comparison of infrastructure as a service providers](http://www.sciencedirect.com/science/article/pii/S0045790617311746) (in press) with my [advisor](http://www.dbms.cs.kumamoto-u.ac.jp/~aritsugi/intro.shtml) which discussed a novel methodology for comparing public cloud virtual machines using established benchmarks and shows workload correlation of the adapted benchmarks with three real analytics application workloads.
* I also published another paper called [Robust Deadline-Constrained Resource Provisioning and Workflow Scheduling Algorithm for Handling Performance Uncertainty in IaaS Clouds](https://dl.acm.org/citation.cfm?id=3148110&CFID=1023126095&CFTOKEN=89513308) and gave a talk about it in Dec. 2017 at the [CloudAM/HDCC](cloudam2017.lncc.br), a [UCC 2017](http://www.depts.ttu.edu/cac/conferences/ucc2017/) Workshop.



<div class="social-icons">

        {% if site.owner.twitter %}
        <a href="http://twitter.com/blabdool{{ site.owner.twitter }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-twitter fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
        {% if site.owner.google_plus %}
        <a href="https://plus.google.com/+BILKISUMUHAMMADBELLO?hl=en{{ site.owner.google_plus }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-google-plus fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
        {% if site.owner.instagram %}
        <a href="http://instagram.com/bilkisumuhammadbello{{ site.owner.instagram }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-instagram fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
        {% if site.owner.github %}
        <a href="http://github.com/blabdool{{ site.owner.github }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-github fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
        {% if site.owner.facebook %}
        <a href="http://facebook.com/bilkisua{{ site.owner.facebook }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-facebook fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
        {% if site.owner.quora %}
        <a href="https://www.quora.com/profile/BILKISU-MUHAMMAD-BELLO{{ site.owner.quora }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-facebook fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
        {% if site.owner.LinkedIn %}
        <a href="https://www.linkedin.com/in/bilkisu-bello-9b534474/{{ site.owner.LinkedIn }}">
            <span class="fa-stack fa-lg">
                <i class="fa fa-circle fa-stack-2x fa-inverse"></i>
                <i class="fa fa-facebook fa-stack-1x"></i>
            </span>
        </a>
        {% endif %}
    </div>
