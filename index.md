---
layout: page
navbar: false
contacts:
  - name: Github
    link: https://github.com/singh-ramanpreet
    icon-class: icon major brands fa-github
  - name: LinkedIn
    link: https://www.linkedin.com/in/singh-ramanpreet
    icon-class: icon major brands fa-linkedin-in
---

<section id="intro" class="wrapper style2 fullscreen fade-up">
  <div class="inner">
    <div class="row gtr-uniform">
      <div class="col-6">
        <h1>{{ site.title }}</h1>
        <p>Physicist, Algorithm Developer, Enthusiastic Coder and Always Learning</p>
          <ul class="actions">
            <li><a href="#one" class="button scrolly">Learn more</a></li>
          </ul>
      </div>
      <div class="col-6"><span class="image fit"><img src="{{ '/images/profile.jpg' | relative_url }}" alt="" /></span></div>
    </div>
  </div>
</section>

<section id="contact" class="wrapper style1 fade-up">
  <div class="inner">
    <h2>Contact</h2>
    <section>
      <ul class="icons">
        {%- for contact in page.contacts %}
        <li><a href="{{ contact.link }}" class="{{ contact.icon-class }}"><span class="label">{{ contact.name }}</span></a></li>{% endfor %}
      </ul>
    </section>
  </div>
</section>