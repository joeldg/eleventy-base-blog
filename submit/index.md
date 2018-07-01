---
layout: layouts/post.njk
title: Submit a hoodie
tags:
  - nav
navtitle: Submit
templateClass: tmpl-post
---
<div class="col col-sm-8">

<p>I will LOVE you if you submit a high-tier or mid-tier hoodie that I don't have!

Add your email here and please post a link to the hoodie.

<i>NOTE: There are millions of hoodies out there, I am mostly interested in high-end and even some mid-tier >$50 hoodies.</i>  
</p>

<form name="contact" method="POST" netlify-honeypot="bot-field" netlify>
    <hidden name="bot-field" />
  <p>
    <label>Email: <input type="text" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <div data-netlify-recaptcha></div>
  <p>
    <button type=”submit”>Send</button>
  </p>
</form>

</div>
