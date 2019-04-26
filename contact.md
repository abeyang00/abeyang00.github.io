---
layout: default
title: 
---

<div class="container">
  <div class="row">
    <div class="col-xs-12 col-sm-8 col-md-6 col-sm-push-2 col-md-push-3 form__container">
      <h2>Contact</h2>
      <form action="//formspree.io/ab3.yang@snu.ac.kr" role="form" method="POST" autocomplete="on">
        <div class="form-group">
          <label for="name">Name</label>
          <input type="text" name="name" class="form-control form-input" placeholder="" required>
        </div>

        <div class="form-group">
          <label for="_replyto">Email</label>
          <input type="email" name="_replyto" class="form-control form-input" placeholder="" required>
        </div>

        <div class="form-group">
          <label for="message">Message</label>
          <textarea id="message" name="message" class="form-control" rows="4" width="100%" placeholder="" required></textarea>
        </div>

        <div>
          <input type="submit" class="btn btn-primary" value="Gönder">
        </div>
      </form>
    </div>
  </div>
</div>
