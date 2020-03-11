---
layout: page_w_header
title:  "Industries"
subtitle: "Ocelot carries a legacy of highly successful partnerships in multiple industries"
background: mediumBackground
industries:
  - title: Healthcare
    linkId: healthcare-section
    link: /industries/healthcare.html
    image: /assets/images/health_care_6x9.jpg
    problem: The healthcare field is constantly evolving and growing. In order to keep up, companies need to collect, manage, analyze, and display massive amounts of data while still maintaining privacy.
    solution: As the amount and variety of data consumed continues to grow, new and innovative solutions are needed to keep up. From ingesting and processing the data to analyzing and visualization, performance and accuracy are key.<br/><br/>Ocelot has experience helping clients in the Healthcare industry adapt and grow to meet their ever changing data needs without compromising privacy standards.
  - title: Utilities
    linkId: utilities-section
    link: /industries/utilities.html
    image: /assets/images/utilities2-6x9.jpg
    problem: When it comes to services in the Utilities industry performance and reliability are of critical to a companies success.
    solution: As more people need access to services more strain is put on Utility companies infrastructure and they need to be able to adapt and scale to be able to support the extra load. IT is a critical piece of that infrastructure that can help companies better monitor their services, react to issues, and maintain contact with their customers.<br/><br/>Ocelot has shown that we have the right skills to help clients keep up with the ever increasing demands they face.
  - title: Financial Services
    linkId: financial-section
    link: /industries/financial_services.html
    image: /assets/images/financials2-6x9.jpg
    problem: Working with a Fortune 500 Financial Client, Oceleot helped accelerate their cloud adoption and modernization of infrastructure
    solution: TBD
  - title: Telecommunications
    linkId: telecom-section
    link: /industries/telecom.html
    image: /assets/images/telecom-6x9.jpg
    problem: Ocelot partnered with a Fortune 500 Telecom Client to help them deliver a modern ordering solution for their Call Centers
    solution: TBD
  - title: Human Resources
    linkId: hr-section
    link: /industries/hr.html
    image: /assets/images/hr.jpg
    problem: Ocelot has helped a local firm modernize their job positng application and aided in integrating that system with the hiring efforts for the State of Missouri
    solution: TBD
---

<div class="container with-padding">
  <div class="content">
    <div class="dashboard">
      <!-- left panel -->
      <div class="dashboard-panel is-one-quarter">
        <aside class="menu">
          <p class="menu-label">
            Industries
          </p>
          <ul class="menu-list">
            {% for industry in page.industries %}
              <li><a href="#{{ industry.linkId }}">{{ industry.title }}</a></li>
            {% endfor %}
          </ul>
        </aside>
      </div>
      <!-- main section -->
      <div class="dashboard-main">
        <section class="section">
          {% for industry in page.industries %}
            {% include industry-summary.html title=industry.title image=industry.image problem=industry.problem solution=industry.solution linkId=industry.linkId link=industry.link %}
          {% endfor %}
        </section>
      </div>
    </div>
  </div>
</div>
