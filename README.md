 MailChimp single opt in wrapper - by Alan Pasho, wordpressdev.net
 
By default embedded forms from MailChimp require double opt in. To create a single 
opt in form one must use a api wrapper. Here I have created a simple form the submits
an email address to the api wrapper via AJAX. jQuery is required for the AJAX call. 
And the MailChimp API class, MCAPI.class.php, can be obtained from 
http://apidocs.mailchimp.com/api/downloads/ 