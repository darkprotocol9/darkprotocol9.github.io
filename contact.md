---
title: Contact
permalink: /contact/
sidebar_link: true
sidebar_sort_order: 5
---

This contact form uses Formspree, so once you hit the "Send" button, you will be redirected to the Formspree page that tells you that the message has been submitted, and a button to return to my blog. Please do not keep re-submitting the form. The confirmation message means that I have gotten the message.

<form
  action="https://formspree.io/f/myzyeyrv"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
