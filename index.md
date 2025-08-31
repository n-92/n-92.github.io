---
layout: default
title: Home
---

<div align="center">

<img src="/assets/img/logo.png" alt="Company logo" width="96" />

# Your Company Name

**We solve <em>real</em> problems with modern software & hardware.**
<br>
From rapid prototypes to production deployments.

[Get a Quote](mailto:hello@yourcompany.com){: .btn }  [See Our Work](/projects){: .btn }

</div>

---

## What we do
- **Custom Software** — Web, mobile, integrations, APIs
- **Cybersecurity & Testing** — Audits, hardening, compliance support
- **IoT & Embedded** — ESP32, sensors, device integrations
- **Data & AI** — Dashboards, ML pipelines, NLP

## Why choose us
- **Speed with quality** — sprints that ship
- **Transparent pricing** — no surprises, ever
- **Own your IP** — you keep the code
- **Clear communication** — weekly updates and demos

## Recent highlights
- Deployed a scalable marketplace handling 50k+ monthly users
- Reduced cloud costs by 37% with architecture optimizations
- Built a BLE mesh demo across 20+ devices for live events

---

## Testimonials
> “They delivered exactly what we needed—on time and on budget.”

> “Security-minded and pragmatic. Great partner for growth.”

---

## Latest posts
{% assign posts = site.posts | slice: 0, 3 %}
{% if posts.size > 0 %}
<ul>
  {% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>— {{ post.date | date: "%b %-d, %Y" }}</small>
    <br>
    <span>{{ post.excerpt | strip_html | truncate: 140 }}</span>
  </li>
  {% endfor %}
</ul>
[All posts](/){: .btn }
{% else %}
*No posts yet.* Create one in `/_posts/`.
{% endif %}

---

Need a quick intro deck? Download our [one-pager](/assets/docs/company-brochure.pdf).
