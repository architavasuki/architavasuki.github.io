---
layout: default
title: Quarter Mile
---

<style>
body {
  background: #fbfbeb;
  font-family: 'Inter', Arial, Helvetica, sans-serif;
  color: #403324;
  margin: 0;
  min-height: 100vh;
}
.nav {
  width: 100%;
  max-width: 750px;
  border-bottom: 1px solid #b3b3ac;
  display: flex;
  justify-content: space-between;
  margin: 2.5rem auto 2.5rem auto;
  padding-bottom: 0.5rem;
}
.nav a {
  color: #403324;
  text-decoration: none;
  font-size: 1.08em;
}
.nav a:hover {
  text-decoration: underline;
}
.center-img {
  display: block;
  margin: 0 auto 2.5rem auto;
  max-width: 420px;
  width: 100%;
  border-radius: 2px;
  height: auto;
}
.essays {
  max-width: 600px;
  margin: 0 auto;
  font-size: 1em;
}
.essays a {
  color: #403324;
  text-decoration: none;
}
.essays a:hover {
  text-decoration: underline;
}
.note {
  margin-top: 1.5rem;
  font-style: italic;
}
.divider {
  margin: 1.6rem 0;
  text-align: center;
  font-size: 1.2em;
}
.newsform {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 400px;
  margin: 1.5rem auto;
  gap: 0.7rem;
}
.newsform label {
  text-align: center;
  font-size: 0.98em;
}
.newsform .inputs {
  display: flex;
  width: 100%;
  gap: 7px;
}
.newsform input[type="email"] {
  flex: 1;
  padding: 6px;
  border: 1px solid #b3b3ac;
  font-size: 1em;
}
.newsform input[type="submit"] {
  padding: 6px 18px;
  border: 1px solid #b3b3ac;
  background: #fbfbeb;
  font-size: 1em;
  cursor: pointer;
  transition: background 0.2s;
}
.newsform input[type="submit"]:hover {
  background: #d3d3cd;
}
</style>
<link href="https://fonts.googleapis.com/css?family=Inter:400,400italic&display=swap" rel="stylesheet">

<div class="nav">
  <a href="/">Writing</a>
  <a href="#subscribe">Subscribe</a>
  <a href="#contact">Contact</a>
</div>

<img src="https://ext.same-assets.com/1232980843/938722091.jpeg" class="center-img" alt="Quarter Mile Cars">

<div class="essays">

[Sample Essay 1](essays/essay1.md)

[Sample Essay 2](essays/essay2.md)

[How To Add Images](essays/add-images.md)

[How To Link to a PDF](essays/pdf-link-demo.md)

<div class="note">Essays listed from newest to oldest.</div>
<div class="divider">* * *</div>

<!-- <form id="subscribe" action="https://buttondown.com/api/emails/embed-subscribe/quartermile" method="post" target="popupwindow" onsubmit="window.open('https://buttondown.com/quartermile', 'popupwindow');return true;" class="newsform">
  <label for="bd-email">Want to get updated when we post new essays? Enter your email here. No spam, just essays.</label>
  <div class="inputs">
    <input type="email" name="email" id="bd-email" required>
    <input type="submit" value="Subscribe">
  </div>
</form> -->

</div>
