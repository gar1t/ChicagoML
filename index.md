---
title: Home
layout: default
permalink: /
nav_order: 1
---

<img src="/assets/images/logo-blue.svg" style="height:60px" class="mt-3">

A community of eningeers, researchers, students, and enthusiasts
working to advance the knowledge and application of machine learning
science.
{: .fs-6 }

![](/assets/images/Chicago_sunrise_1.jpg)

<b>Chicago ML</b> hosts meetups, workshops, and symposiums to support
learners and experts alike. We are an all-volunteer organization and
rely on contributions of time and resources from our members and
sponsoring organizations. Membership is free and without
obligation---simply follow the link below to sign up on our Meetup
page.

Chicago ML fosters an open and welcoming environment to everyone
regardless of age, body size, disability, ethnicity, gender identity
and expression, level of experience, nationality, personal appearance,
race, religion, or sexual identity and orientation.

<a href="https://www.meetup.com/Chicago-ML/" class="btn btn-primary py-2 px-4 mx-1 mt-2" title="View our upcoming events and register.">Visit us on Meetup <i class="fab fa-meetup fa-lg ml-1"></i></a>
<a href="https://bit.ly/2S0zFAP" class="btn btn-default py-2 px-4 mx-1 mt-2" title="Ask questions, make friends.">Join us on Slack <i class="fab fa-slack-hash fa-lg ml-1"></i></a>
<a href="https://bit.ly/2GQlWKS" class="btn btn-default py-2 px-4 mx-1 mt-2" title="Let us know what you'd like to see or present.">Propose a Talk <i class="far fa-lightbulb fa-lg ml-1"></i></a>

---

{% for post in site.tags.event limit:5 %}

# [{{post.title}}]({{post.url}})
{: .event-title }

{{ post.date | date:"%A, %B %d, %Y"}} - {{ post.time }} - {{ post.host }}

{{ post.excerpt }}

{%- if post.registration_url -%}
<a href="{{ post.registration_url }}" class="btn btn-secondary py-2 px-4 mx-1">Register for this event <i class="fas fa-calendar-plus ml-1"></i></a>
{%- endif -%}
<a href="{{ post.url }}" class="btn btn-default py-2 px-4 mx-1">Event details <i class="fas fa-info-circle ml-1"></i></a>

---

{% endfor %}
