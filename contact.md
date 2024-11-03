---
title: Contact
permalink: /contact/
sidebar_link: true
sidebar_sort_order: 5
---

Once you hit the "Send" button, you will be redirected to a page that tells you that the message has been submitted, and a button to return to this page. Please do not keep re-submitting the form. The confirmation message means that I have gotten the message. Your message might still be in the textbox

<form
  action="https://formspree.io/f/myzyeyrv"
  method="POST"
  style="max-width: 400px; margin: auto; padding: 1em; border: 1px solid #ccc; border-radius: 5px; background-color: #f9f9f9;"
>
  <h2 style="text-align: center; color: #333;">Contact Me</h2>

  <label style="display: block; margin-bottom: 0.5em; color: #333;">
    Your email:
    <input type="email" name="email" required
      style="width: 100%; padding: 0.5em; margin-top: 0.3em; border: 1px solid #ccc; border-radius: 3px; box-sizing: border-box;"
    >
  </label>

  <label style="display: block; margin-bottom: 0.5em; color: #333;">
    Your message:
    <textarea name="message" required
      style="width: 100%; padding: 0.5em; margin-top: 0.3em; border: 1px solid #ccc; border-radius: 3px; box-sizing: border-box; min-height: 100px;"
    ></textarea>
  </label>

  <!-- Submit button styling -->
  <button type="submit"
    style="width: 100%; padding: 0.7em; background-color: #4CAF50; color: white; border: none; border-radius: 3px; font-size: 1em; cursor: pointer;"
  >
    Send
  </button>
</form>

----------------------------

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
