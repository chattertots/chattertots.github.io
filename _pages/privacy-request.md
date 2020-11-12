---
sitemap:
  lastmod: 2020-11-11
  priority: 0.6
  changefreq: 'yearly'
  exclude: 'no'
permalink       : /privacy-request.html
last_modified_at: 2020-11-11
title           : Personal data request
share           : false
author          : Chattertots
author_profile  : false
layout          : single
classes         : wide
sidebar:
  nav: smallsidenav
header:
  overlay_color: "#C2DD5B"
#header:
#  overlay_color: #000
#  overlay_filter: 0.1
#  overlay_image: /assets/images/page-features/webp/60/contact-abstract.jpg
#  caption: "Photo credit: [**Steve Johnson**](https://www.pexels.com/@steve)"
---

Please use this form to request to view/edit/delete personal information that Chattertots may hold


<form action="https://formspree.io/mgeodkpl" method="POST">
  <label for="name">
    Your Name:
    <input type="text" name="name">
  </label>
  <label for="telephone">
    Your phone number:
			<input type="telephone" name="telephone" id="telephone">
  </label>
  <label for="_replyto">
    Your email:
    <input type="text" name="_replyto">
  </label>
  <label for="message">
    How can we help you?:
    <textarea  name="message"></textarea>
  </label>

  <!-- your other form fields go here -->
  <input type="hidden" name="_next" value="/thanks" />
  <input type="hidden" name="_subject" value="Personal data request" />
  <input type="text" name="_gotcha" style="display: none;" val=""/>
  <button type="submit" class="btn btn--primary">Send</button>
</form>