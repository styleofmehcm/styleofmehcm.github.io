---
title: "Contact"
permalink: "/contact.html"
---

<form action="https://formspree.io/f/xdovzevn" method="POST">    
<p>Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>


<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xdovzevn"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <div class="col-md-6">
    <textarea name="message"></textarea>
    </div>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>


<!-- modify this form HTML and place wherever you want your form -->
<form action="https://formspree.io/f/xdovzevn" method="POST">
<p>Please send your message to {{site.name}}. We will reply as soon as possible!</p>
  <div class="form-group row">
  <div class="col-md-6">
  <input class="form-control" type="text" name="name" placeholder="Name*" required>
  </div>
  <div class="col-md-6">
  <input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
  </div>
  </div>
  <textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    

  <button type="submit">Send</button>
</form>