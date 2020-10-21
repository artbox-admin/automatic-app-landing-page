---
layout: page
title: Contact
include_in_header: false
---

<form action="https://formspree.io/f/mzbkreke" method="POST">
  <input type="text" name="name">
  <input type="email" name="_replyto">
  <input type="submit" value="Send">
</form>

<form name="sentMessage" id="contactForm" novalidate action="https://formspree.io/f/mzbkreke" method="post">
    <input type="hidden" name="_subject" value="Artbox Support" />
    <input type="text" name="_gotcha" style="display:none" />
    <div class="control-group">
        <div class="form-group floating-label-form-group controls">
        <label></label>
        <input type="text" class="form-control" placeholder="" id="name" name="name" required data-validation-required-message="">
        <div class="help-block text-danger"></div>
        </div>
        <div class="form-group floating-label-form-group controls">
        <label></label>
        <input type="email" class="form-control" placeholder="" id="email" name="email" required data-validation-validemail-message="" data-validation-required-message="">
        <div class="help-block text-danger"></div>
        </div>
        <div class="form-group floating-label-form-group controls">
        <label></label>
        <textarea rows="5" class="form-control" placeholder="" id="message" name="message" required data-validation-required-message=""></textarea>
        <div class="help-block text-danger"></div>
        </div>
    </div>
    <br>
    <div id="success"></div>
    <div class="form-group">
        <button type="submit" class="btn btn-primary" id="sendMessageButton">Send</button>
    </div>
</form>
action="https://formspree.io/f/mzbkreke"
