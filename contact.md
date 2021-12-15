---
title: Contact
layout: contact
description: Contact
excerpt: We're open til 9pm 7 days a week.
intro_image: "images/illustrations/reading.svg"
intro_image_absolute: true
intro_image_hide_on_mobile: true
---


For support issues please email us at [help@foodit.com](mailto:help@foodit.com) or call us on the number above.

# MAKE SALES ENQUIRY


<form method="POST" action="https://foodit-prod.appspot.com/api/form/contactUs" class="validator ajax">
  <div class="success-message">
    <h2>Thanks for contacting us</h2>
    <p>A sales representative will get in touch with you soon.</p>
  </div>
  <div class="field-wrapper name">
    <input type="text" name="name" placeholder="Your full name" data-validation-minlength="2">
    <p class="error__message">Add at least your name.</p>
  </div>
  <div class="field-wrapper email">
    <input type="email" name="email" placeholder="Your email address" data-validation-regex="^[\w-\.]+@([\w-]+\.)+[\w-]+$">
    <p class="error__message">The email address provided is not correct</p>
  </div>
  <div class="field-wrapper phone">
    <input type="text" name="phone" placeholder="Your phone number" data-validation-regex="^(?:(?:\(?(?:0(?:0|11)\)?[\s-]?\(?|\+)44\)?[\s-]?(?:\(?0\)?[\s-]?)?)|(?:\(?0))(?:(?:\d{5}\)?[\s-]?\d{4,5})|(?:\d{4}\)?[\s-]?(?:\d{5}|\d{3}[\s-]?\d{3}))|(?:\d{3}\)?[\s-]?\d{3}[\s-]?\d{3,4})|(?:\d{2}\)?[\s-]?\d{4}[\s-]?\d{4}))(?:[\s-]?(?:x|ext\.?|\#)\d{3,4})?$">
    <p class="error__message">The phone number doesn't appear to be correct</p>
  </div>
    <div class="field-wrapper restaurant">
      <input type="text" name="restaurant" placeholder="Restaurant name">
    </div>
    <div class="field-wrapper postCode">
      <input type="text" name="postCode" placeholder="Postcode">
    </div>
    <div class="field-wrapper enquiry">
      <textarea name="enquiry" placeholder="Which products are you interest in?"></textarea>
    </div>
  <button class="submit button-primary">
      Submit
  </button>
</form>
