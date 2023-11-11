---
title: İletişim
type: page
---

<!-- modify this form HTML and place wherever you want your form -->

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mgejbwpz" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Ad Soyad</label>
    <input type="text" name="name" id="full-name" placeholder="Ad Soyad" required="">
    <label for="email-address">Email Adresiniz</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@email.com" required="">
    <label for="message">Mesajınız</label>
    <textarea rows="5" name="message" id="message" placeholder="Mesajınızı buraya yazabilirsiniz." required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Gönder">
</form>
