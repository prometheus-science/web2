---
layout: page
title: Contact Us
share-title: Prometheus Science | Contact Us
---

<script src="https://www.google.com/recaptcha/api.js" async defer></script>
<script>enableSubmitContact = function(){ document.getElementById("submit_contact").disabled = false; }</script>

For any consulting inquiries, please email [contact@prometheus-science.com](mailto:contact@prometheus-science.com?subject=consulting inquiry)

Note that before any work can be performed, a (virtual) meeting is usually held to gather requirements and discuss your needs.


<div style="text-align: center;">
<a href="https://calendly.com/promethsci-meeting/30min" class="schedule-btn actionbtn">
  <span class="far fa-calendar-check" aria-hidden="true"></span>
  Schedule Meeting
</a>
</div>


You can also send us a message using this form:



<form action="https://formspree.io/f/mknpbwnr" method="POST" class="form" id="contact-form">
  <div class="row">
    <div class="col-6">
      <input type="email" name="email" required="required" class="form-control input-lg" placeholder="Email" title="Email" style="margin-bottom: 15px;">
    </div>
    <div class="col-6">
      <input type="text" name="name" class="form-control input-lg" placeholder="Name" title="Name" style="margin-bottom: 15px;">
    </div>
  </div>
  <textarea type="text" name="content" class="form-control input-lg" placeholder="Message" title="Message" required="required" rows="3"></textarea>
  
  <div style="margin-top: 5px; display: flex; margin-bottom: 15px; font-size: 0.7rem;">
    <input type="checkbox" id="formspree-subscribe" name="formspree-subscribe" value="agree" checked style="margin-top: 2px; margin-right: 4px;" />
    <label for="formspree-subscribe">Sign up to our newsletter (unsubscribe at any time)</label>
  </div>

  <div class="g-recaptcha" data-sitekey="6LcT5_kfAAAAAFhN2wtb9wCcLRSptb6-aot-BaFo" data-callback="enableSubmitContact"></div>
  <!--
  <input type="hidden" name="_feedback.success.title" value="Thanks for contacting Prometheus Science, we'll be in touch shortly!" />
  <input type="hidden" name="_email.from" value="Formspark Prometheus Science" />
  <input type="hidden" name="_feedback.error.title" value="An error occurred (did you check the &quot;I'm not a robot&quot; box?)" />
-->
  <br/>
  <button id="submit_contact" type="submit" class="btn btn-lg btn-primary" disabled>Submit</button>
</form>
