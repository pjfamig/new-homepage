---
layout: default
title: Contact
---

<h2>{{ page.title }}</h2>


<div class="row">

<div class="col-xs-12">

<!-- <div class="success_box">All of the fields were successfully validated!</div> -->
<div class="error_box"></div>
	
<form name="contact_form" action="http://getsimpleform.com/messages?form_api_token=03c0f6779ee6fe1dd9dcd449fdc86812" method="POST">

  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='http://localhost:4000/contact/thank-you/' />

  <!-- all your input fields here.... -->	
	    <p><input type="text" class="form-control" placeholder="Name" name="name"></p>
		<p><input type="text" class="form-control" placeholder="Email" name="email"></p>
 		<p><textarea name="message" placeholder="Enter a message..." class="form-control" rows="9"></textarea></p>
	  <p><input type='submit' value='Send' class="btn btn-small btn-success"/></p>
	</div>
</form>

</div>

