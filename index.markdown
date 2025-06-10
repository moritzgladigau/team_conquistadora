---
layout: default
title: Segelteam Asso 99
---

<!-- Hero -->
<section class="hero-large">
  <div class="hero-text">
    <h1>Compete. Win. Sail!</h1>
    <p class="hero-subtitle">
      Wir sind das Segelteam Asso 99 vom Chiemsee – jung, schnell und motiviert.
    </p>
  </div>
</section>

<section class="events">
  <h2> </h2>
  <div class="wrapper">
    <div class="items">
      <div class="item" tabindex="0" style="background-image: url('{{ 'team_conquistadora/assets/images/asso99-erste-saison-2021.jpg' | relative_url }}')"></div>
      <div class="item" tabindex="0" style="background-image: url('{{ 'team_conquistadora/assets/images/asso99-crew-2021.jpg' | relative_url }}')"></div>
      <div class="item" tabindex="0" style="background-image: url('{{ 'team_conquistadora/assets/images/0B98E31E-59A5-4614-B557-2934D3CF49F1.jpg' | relative_url }}')"></div>
      <div class="item" tabindex="0" style="background-image: url('{{ 'team_conquistadora/assets/images/376EA14F-E7C6-45C6-AEB0-7BBAEF39FD21.jpg' | relative_url }}')"></div>
      <div class="item" tabindex="0" style="background-image: url('{{ 'team_conquistadora/assets/images/07d0323b-9d4f-4382-96ba-8e66a735ab6e.jpg' | relative_url }}')"></div>
    </div>
  </div>
</section>



<!-- Latest Results 
<section class="section-results" id="results">
  <h2>Latest Regatta Results</h2>
  <table>
    <thead>
      <tr><th>Place</th><th>Team</th><th>Points</th></tr>
    </thead>
    <tbody>
      <tr><td>1</td><td>Sea Wolves</td><td>25</td></tr>
      <tr><td>2</td><td>Nauta Pacing</td><td>32</td></tr>
      <tr><td>3</td><td>Aquaholics</td><td>37</td></tr>
    </tbody>
  </table>
</section>
-->

<!-- Upcoming Events -->
<section class="section-events" id="events">
  <h2>Upcoming Events</h2>
  <div class="cards">
    <div class="card">
      <div class="date">
        <div class="month">Sep</div>
        <div class="day">06</div>
      </div>
      <div class="info">
        <h3>Centomiglia</h3>
        <p>Gardasee</p>
      </div>
    </div>
    <div class="card">
      <div class="date">
        <div class="month">Sep</div>
        <div class="day">25</div>
      </div>
      <div class="info">
        <h3>Hungarian Open Asso99</h3>
        <p>Spartacus, Balatonföldvár</p>
      </div>
    </div>
  </div>
  <p class="view-all"><a href="/events.html">View All</a></p>
</section>


<section class="blog">
  <h2>Neuigkeiten</h2>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.date | date: "%d.%m.%Y" }} – {{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</section>
