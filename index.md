---
layout: page
title: Morgan Powell
tagline: Mechanical Engineering BEng (Hons)
---
{% include JB/setup %}

<div class="row">
    <div class="col-md-3">
        <img src="assets/img/profile.jpg" 
             alt="Graduate of Northumbria University"
             class="img-circle" >
    </div>
    <div class="col-md-9">

I am a hard working engineering graduate who is looking for employment within an engineering related industry. Upon my graduation in June 2014, I receive an upper second class honours degree in Mechanical Engineering, awarded by Northumbria University. I am a naturally confident person with excellent communication skills, and I feel I would be a great asset to any company, small or large.
I have particular interests in 3D modelling and rapid prototyping.

    </div>
</div>

<div class="row">
    <div class="col-md-6">

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li>
        <span>{{ post.date | date_to_string }}</span> &raquo; 
        <a href="{{ BASE_PATH }}{{ post.url }}" title="{{post.title}} : {{post.tagline}}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
    
    </div>
    <div class="col-md-6">

## Links

* [Linked In][linkedin]
* [Northumbria University Course][mecheng]

    </div>
</div>


[linkedin]: http://uk.linkedin.com/pub/morgan-powell/88/811/6a7 "Morgan Powell's Linked In Profile"
[mecheng]: http://www.northumbria.ac.uk/study-at-northumbria/courses/mechanical-engineering-uusmee1/ "Mechanical Engineering BEng (Hons)"