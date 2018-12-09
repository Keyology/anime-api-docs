# Authentication

 Welcome to Anime API this page documents how to authenticate user using our API endpoints.

to authenticate user you can either use fetch and send a form name=email && named name=password, or you can use postman and send the email and password over as json 

## Route endpoint

``` http://localhost:4000/signup ```

exaple of sending user data over in json 

### send a post request to this endpoint

``` 
{
	"email":"Enter email here",
	"password": "Enter password here "

	
}
```

To login user  you can use this Route endpoint: 

```http://localhost:4000/login ```

``` 

Example of sending login info in json format using postman:
### send a post request to this endpoint

{
    "email":"Enter email here",
	"password": "Enter password here "


}

```

