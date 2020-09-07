Here is a list of Endpoints to access API
This API can be test using a pack like XAMPP with Curl extension enabled.
Considering that our API is installed with in our local host computer where it's address is
"http://localhost/mailerlite"
and
"mailerlite"
is folder our files exist. With following Endpoints we can access Subscriber and Fields resources.

Subscribers Resources
To get a list subscribers
// http://localhost/mailerlite/api/Controller.php? action = all_subscribers
To get a subscriber
// http://localhost/mailerlite/api/Controller.php? action = single_subscriber
To insert a subscriber
// http://localhost/mailerlite/api/Controller.php? action = insert
To update a subscriber
// http://localhost/mailerlite/api/Controller.php? action = update
To delete a subscriber
// http://localhost/mailerlite/api/Controller.php? action = delete
Field Resources
To get a subscriber's fields based on subscriber_id. subscriber_id is a variable containing subscriber id
// http://localhost/mailerlite/api/Controller.php? action = sub_fields &id = subscriber_id
To get a field based on field_id. field_id is a variable containing field id
// http://localhost/mailerlite/api/Controller.php? action = single_field &id=field_id
To insert a field
// http://localhost/mailerlite/api/Controller.php?action = insert_field
To update a field
// http://localhost/mailerlite/api/Controller.php?action = update_field
To delete a field
// http://localhost/mailerlite/api/Controller.php?action = delete_field
