---
title: "Ask Me"
url: "/ask_me/"
description: "How to get in touch with me!"
showShareButtons: false
ShowReadingTime: false
ShowBreadCrumbs: false
ShowPostNavLinks: false
ShowToc: false
---

I'm happy to chat about research, potential collaborations, or anything else. 
You can reach out to me via [email](mailto:samuele.ruffino@gmail.com), [LinkedIn](https://www.linkedin.com/in/samuele-ruffino/), or simply drop a message using the form below. Looking forward to connecting!

<form
  action="https://formspree.io/f/samuele.ruffino@gmail.com"
  method="POST"
  class="contact-form"
>
  <label>
    Name
    <input type="text" name="name" placeholder="Your name" required />
  </label>
  <label>
    Email
    <input type="email" name="email" placeholder="your@email.com" required />
  </label>
  <label>
    Message
    <textarea name="message" rows="6" placeholder="What's on your mind?" required></textarea>
  </label>
  <button type="submit">Send message</button>
</form>

<style>
.contact-form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 520px;
  margin-top: 1.5rem;
}
.contact-form label {
  display: flex;
  flex-direction: column;
  gap: .35rem;
  font-size: .9rem;
  font-weight: 500;
}
.contact-form input,
.contact-form textarea {
  padding: .55rem .75rem;
  border: 1px solid var(--border);
  border-radius: var(--radius);
  background: var(--entry);
  color: var(--primary);
  font: inherit;
  font-size: .9rem;
  resize: vertical;
}
.contact-form input:focus,
.contact-form textarea:focus {
  outline: 2px solid #2563eb;
  outline-offset: -1px;
}
.contact-form button {
  align-self: flex-start;
  padding: .5rem 1.4rem;
  background: var(--primary);
  color: var(--theme);
  border: none;
  border-radius: var(--radius);
  font: inherit;
  font-size: .9rem;
  font-weight: 600;
  cursor: pointer;
  transition: opacity .15s ease;
}
.contact-form button:hover { opacity: .8; }
</style>