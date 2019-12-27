---
layout: page_w_header
title:  "Careers with Ocelot"
subtitle: "Ocelot has opportunities for developers of all skill levels utilizing many different skills and technologies"
benefits:
  - title: Insurance
    icon: fa-notes-medical
  - title: PTO
    icon: fa-umbrella-beach
  - title: 401K
    icon: fa-piggy-bank
  - title: Paid Overtime
    icon: fa-hand-holding-usd
  - title: Parental Leave
    icon: fa-baby-carriage
culture:
  - title: Technology First
    icon: fa-laptop-code
  - title: Never an Island
    icon: fa-users
  - title: Work your Passion
    icon: fa-smile-beam
  - title: Strong Relationships
    icon: fa-handshake
---

{% include icon-list.html title="Culture" id="culture" section="is-medium" icons=page.culture %}

{% include icon-list.html title="Benefits" id="benefits" section="is-medium" icons=page.benefits %}

<section class="hero is-medium">
  <div class="hero-body">
    <div class="container has-text-centered">
      <h1 class="title">Open Positions</h1>
      <div class="columns">
        <div class="column is-one-third">
          {% include card.html title="Full Stack Engineer" description="For developers who are comfortable building an app from UI to API, and Database to Cloud provisioning." cardImage="/assets/images/fullstack.jpeg" route="/careers/full-stack-developer" applyRoute="https://www.indeed.com/job/full-stack-developer-cloud-native-b85dc9073f5bdf8e" %}
        </div>
        <div class="column is-one-third">
          {% include card.html title="Big Data Engineer" description="For developers who are comfortable processing terabytes of data. You know your Kafka from your Spark." cardImage="/assets/images/bigdata.png" route="/careers/big-data-engineer" applyRoute="https://www.indeed.com/job/big-data-engineer-18a7c0d744835ec4" %}
        </div>
        <div class="column is-one-third">
          {% include card.html title="Cloud Engineer" description="For developers who are comfortable enabling and expanding Cloud adoption and proficiency via automation and best practices." cardImage="/assets/images/cloudengineer.jpg" route="/careers/cloud-engineer" applyRoute="https://www.indeed.com/job/cloud-engineer-9ba60935db492951" %}
        </div>
      </div>
    </div>
  </div>
</section>
