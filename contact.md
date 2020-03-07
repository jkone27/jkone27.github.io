---
permalink: /contact/
---

<!-- https://github.com/toperkin/staticFormEmails didnt work :( -->

<form
  action="https://formspree.io/xrgkvpew"
  method="POST"
>
  <label>
    Your Name:
    <input type="text" name="name">
  </label>
  <label>
    Your Email:
    <input type="email" name="_replyto">
  </label>
  <label>
    Message:
    <textarea name="message"></textarea>
  </label>
  <input type="submit" value="Send">
</form>
