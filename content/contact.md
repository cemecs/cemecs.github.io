---
title: İletişim
---

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mgejbwpz" method="post">
  <fieldset id="fs-frm-inputs">
    <div class="form-group">
      <label for="full-name">Ad Soyad</label>
      <input type="text" name="name" id="full-name" class="form-control" placeholder="Ad Soyad" required="">
    </div>
    <div class="form-group">
      <label for="email-address">Email Adresiniz</label>
      <input type="email" name="_replyto" id="email-address" class="form-control" placeholder="email@email.com" required="">
    </div>
    <div class="form-group">
      <label for="message">Mesajınız</label>
      <textarea rows="5" name="message" id="message" class="form-control" placeholder="Mesajınızı buraya yazabilirsiniz." required=""></textarea>
    </div>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
    <input type="submit" value="Gönder" class="btn btn-primary">
  </fieldset>
</form>

<div class="container">
  <!-- CHANGE THE URL HERE -->
  <form action="https://app.99inbound.com/e/123" method="POST" target="_blank">
    <h3 style="text-align: center;">Contact Us</h3>

  <div class="form-group">
    <label for="email">Email address</label>
    <input name="email" type="email"  class="form-control" id="email" placeholder="Enter email" required>
   </div>

  <div class="form-group">
    <label for="message">Message</label>
    <textarea name="message" class="form-control" id="message" rows="5" placeholder="Enter message" required></textarea>
  </div>

<button type="submit" class="btn btn-primary float-right">Submit</button>

  </form>
</div>
