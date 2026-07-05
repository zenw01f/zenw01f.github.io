---
title: "Asena Security"
layout: splash
permalink: /
hidden: true
---

<style>
.home-hero{padding:52px 0 40px;}
.home-hero h1{font-size:2.1em;line-height:1.25;margin:0 0 22px;max-width:680px;}
.home-hero p{font-size:1.08em;line-height:1.75;max-width:700px;margin:0 0 30px;opacity:0.9;}
.home-cta .btn{margin-right:12px;margin-bottom:10px;}
.section-label{
  text-transform:uppercase;letter-spacing:0.08em;
  font-size:0.76rem;font-weight:700;
  color:#4fd9d6;margin:0 0 18px;display:block;
}
.home-section{
  padding:36px 0;
  border-top:1px solid rgba(255,255,255,0.1);
  margin-top:8px;
}
.start-here-grid{
  display:grid;grid-template-columns:1fr 1fr;gap:18px;
}
.start-card{
  background:rgba(255,255,255,0.04);
  border:1px solid rgba(255,255,255,0.1);
  border-radius:6px;padding:20px 22px;
}
.start-card .card-tag{
  font-size:0.72rem;color:#4fd9d6;
  text-transform:uppercase;letter-spacing:0.05em;
}
.start-card h3{margin:8px 0;font-size:1.05em;}
.start-card p{margin:0;font-size:0.92em;opacity:0.7;}
.start-card a{color:inherit;}
.start-card a:hover{color:#4fd9d6;}
.post-list{list-style:none;margin:0;padding:0;}
.post-item{
  display:flex;gap:22px;
  padding:16px 0;
  border-bottom:1px solid rgba(255,255,255,0.07);
}
.post-item:last-child{border-bottom:none;}
.post-date{flex:0 0 110px;font-size:0.85em;opacity:0.5;padding-top:3px;}
.post-meta h3{margin:0 0 5px;font-size:1.08em;}
.post-meta p{margin:0;font-size:0.91em;opacity:0.6;}
.topic-pills{display:flex;flex-wrap:wrap;gap:10px;}
.topic-pill{
  display:inline-block;padding:8px 18px;
  border:1px solid rgba(255,255,255,0.15);
  border-radius:20px;font-size:0.88em;
  color:inherit;
}
.topic-pill:hover{border-color:#4fd9d6;color:#4fd9d6;text-decoration:none;}
@media(max-width:640px){
  .start-here-grid{grid-template-columns:1fr;}
  .post-item{flex-direction:column;gap:4px;}
  .post-date{flex:none;}
}
</style>

<div class="home-hero">
  <h1>Senior cybersecurity perspective. Forged in high-stakes environments.</h1>
  <p>Asena Security is authored by a cybersecurity professional whose career spans 20+ years in IT and information security — much of it inside financial institutions where the cost of a misstep is measured in regulatory action and lost trust, not just downtime. The content here serves the full range: startups getting their security foundation right, practitioners at every stage of their career, and the mentees and interns who deserve straight, experience-backed guidance on how this field actually works.</p>
  <div class="home-cta">
    <a href="#start-here" class="btn btn--primary btn--large">Start Here</a>
    <a href="/posts/" class="btn btn--inverse btn--large">Read the Blog</a>
  </div>
</div>

<div class="home-section" id="start-here">
  <span class="section-label">New here? Start with these</span>
  <div class="start-here-grid">
    <div class="start-card">
      <div class="card-tag">Career</div>
      <h3><a href="/cybersecurity/starting-your-cybersecurity-career/">Starting Your Cybersecurity Career</a></h3>
      <p>What a SOC actually is, why entry-level shift work is the fastest way in, and how to think about the path before you invest thousands of hours.</p>
    </div>
    <div class="start-card">
      <div class="card-tag">Mentoring</div>
      <h3><a href="/cybersecurity/the-learning-hack-taking-it-one-step-at-a-time/">The Learning Hack — Taking It One Step at a Time</a></h3>
      <p>How to approach any new security concept or tool without getting overwhelmed — set a goal, then work it in small chunks.</p>
    </div>
  </div>
</div>

<div class="home-section" id="latest">
  <span class="section-label">Latest Posts</span>
  <ul class="post-list">
    {% for post in site.posts limit:5 %}
    <li class="post-item">
      <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <div class="post-meta">
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        {% if post.excerpt %}<p>{{ post.excerpt | markdownify | strip_html | truncate: 130 }}</p>{% endif %}
      </div>
    </li>
    {% endfor %}
  </ul>
</div>

<div class="home-section" id="topics">
  <span class="section-label">Browse by Topic</span>
  <div class="topic-pills">
    <a class="topic-pill" href="/tags/#mentoring">Career &amp; Mentoring</a>
    <a class="topic-pill" href="/tags/#passwords">Passwords &amp; Hygiene</a>
    <a class="topic-pill" href="/categories/">All Categories</a>
    <a class="topic-pill" href="/tags/">All Tags</a>
  </div>
</div>
