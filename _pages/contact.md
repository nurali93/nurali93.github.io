---
layout: page
title: Drop me a Message! (Yeah it's ugly i know)
permalink: /contact/
---


<form id="contact-form" class="form" action="https://getsimpleform.com/messages?form_api_token=3f94cc4672c1e8cf908c3ee9d55e7f06" method="POST" enctype="multipart/form-data">
  <ul class="contact-ul">
      <li class="contact-li">
          <label class="contact-label" for="name">Name:</label>
          <input type="text" placeholder="Your name" id="name" class="contact-input" name="name" tabindex="1"/>
      </li>
      <li class="contact-li">
          <label class="contact-label" for="email">Email:</label>
          <input type="email" placeholder="Your email" id="email" class="contact-input" name="email" tabindex="2"/>
      </li>
      <li class="contact-li">
          <label class="contact-label" for="message">Message:</label>
          <textarea class="contact-textarea" placeholder="Your message" class="contact-input" rows="4" id="message" name="message" tabindex="3"></textarea>
      </li>

  </ul>
  <input type="submit" value="Send" id="submit"/>
  <input type="hidden" name='redirect_to' value="#" />
</form>

Business? Freelance? Consultation? Friendship? Anything =)

<style>

.form {
  width: 100%;
}

.contact-li {
  list-style: none;
}

.contact-input {
  border:none;
  border-bottom: 1px solid #eee;
  transition-duration: 0.3s;
  width: 100%;
}

.contact-input:focus {
  outline:none;
  border-bottom: 1px solid #fa8072;
}

.contact-label {
  display: block;
}

ul.contact-ul {
  margin: 0;
  padding: 1rem 2rem;
  width: 100%
}

#submit {
  border:none;
  background-color: #fa8072;
  padding: 5px 15px;
  color: #eee;
  opacity: 0.8;
}

#submit:hover {
  opacity: 1;
  cursor: pointer;
}


#contact-form {
  border: 1px solid #aaa;
  display: inline-flex;
  margin-bottom: 1em;
}

</style>
