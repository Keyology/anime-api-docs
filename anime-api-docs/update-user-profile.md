# Allow user change email

To allow users to change email send a ```put request``` to this url endpoint:

``` 
http://localhost:4000/userprofile
```

This API endpoint will search to see if the user email exsit inside the database and if is does it will change it to a new email.

you can use fetch and send a form name =email for the old email and form name = new email

### here is an example of how to use this api using postman

```
{
	"email":"enter user orginalemail here",
	"newemail": "enter user new email here "
	
	

	
} 
```
