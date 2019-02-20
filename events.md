---
layout: default
title: Events
nav_order: 10
---

# Events

![](/assets/images/meetup-1.jpg)

Chicago ML hosts regular meetups and workshops. We use Meetup.com for
all events.

<a href="https://www.meetup.com/Chicago-ML/events/calendar/" class="btn btn-primary py-2 px-4 mx-1 mt-2" title="View our upcoming events.">Upcoming events on Meetup <i class="far fa-calendar-alt fa-lg ml-1"></i></a>
<a href="https://bit.ly/2GQlWKS" class="btn btn-default py-2 px-4 mx-1 mt-2" title="Let us know what you'd like to see or present.">Request a topic for an upcoming event <i class="far fa-lightbulb fa-lg ml-1"></i></a>

## Featured Events

{% for post in site.tags.event limit:5 %}

### [{{post.title}}]({{post.url}})
{: .event-title }

{{ post.date | date:"%A, %B %d, %Y"}} - {{ post.time }} - {{ post.host }}

{% endfor %}
