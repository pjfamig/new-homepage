---
layout: default
title: Contact
---

<h2>{{ page.title }}</h2>


<div class="row">
<form action="http://getsimpleform.com/messages?form_api_token=03c0f6779ee6fe1dd9dcd449fdc86812" method="post">

  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='http://localhost:4000/contact/thank-you/' />

  <!-- all your input fields here.... -->	
	<div class="col-xs-12">
	    <p><input type="text" class="form-control" placeholder="Name" name="name" style=""></p>
 		<p><textarea name="message" placeholder="Enter a message..." class="form-control" rows="9"></textarea></p>
	  <p><input type='submit' value='Send' class="btn btn-small btn-success"/></p>
	</div>
</form>
</div>