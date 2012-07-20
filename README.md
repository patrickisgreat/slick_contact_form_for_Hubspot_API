Slick-Contact-Form-integrated-for-the-Hubspot-Leads-API
=======================================================

This is the Wordpress Slick Contact form integrated for the Hubspot Leads API

Here I have utilized the HaPiHP API client within the Wordpress slick contact form plugin to create Leads within Hubspot. 

I've included the client in this repository in /hap

This bit of code allows you to harvest the minimum required fields and send the data to Hubspot's software along with a tracking cookie that is created by their Javascript and the REMOTE_ADDR

See hap/example.php for usage examples on instantiating a Leads object and which methods you can call. 

Instead of attaching another php file to the submit event I wrote this integration code into the slick_mail.php that is fired on submit. 

Enjoy instant integration with Hubspot in your wordpress site. 