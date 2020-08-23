# Login Control 

Custom Home Assistant component for clearing all tokens of specific user 

Usage:

1. Get the User ID of the user that you want to clear (In HA, go to Configuration -> Persons -> Users -> Press on your user name. Window will open that will show your ID.)
2. Call `clear_refresh_tokens` service with `user_id` parameter with User ID that you retrieved in step 1.
