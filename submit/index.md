---
layout: layouts/post.njk
title: Submit a hoodie
tags:
  - nav
navtitle: Submit
templateClass: tmpl-post
---
<div class="col col-sm-8">

<h2>Did I miss one????</h2>

<p>I will LOVE you if you submit a high-tier or mid-tier hoodie that I don't have!

Add your email here and please post a link to the hoodie.

<i>NOTE: There are millions of hoodies out there, I am mostly interested in high-end (>$100) and even some mid-tier (>$50) hoodies.

Typically I only will link to the classic gray version of the hoodie as most retailers will have multiple colors. So please don't send links to every color.
</i>  

Thank you so much!

</p>

<form name="contact" method="POST" netlify-honeypot="bot-field" netlify>
    <hidden name="bot-field" />
  <p>
    <label>Your Email: <input type="text" name="email" /></label>
  </p>
  <p>
    <label>Message+link: <textarea name="message"></textarea></label>
  </p>
  <div data-netlify-recaptcha></div>
  <p>
    <button type=”submit”>Send</button>
  </p>
</form>

</div>
